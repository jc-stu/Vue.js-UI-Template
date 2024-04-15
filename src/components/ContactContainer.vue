<template>
  <v-container fluid>
    <v-row class="d-flex justify-center">
      <v-col class="text-center white--text">
        <span></span>
        <h1>CONTACT</h1>
        <v-col class="d-flex justify-center flex-column col-sm-12 col-12 col-md-12">
          <v-col class="d-flex justify-start justify-sm-center justify-md-center justify-lg-center justify-xl-center align-center">
            <h3>地址：</h3>
            <span class="contact-info-typography ps-1">
              重庆市南岸区崇文路2号重庆邮电大学</span
            >
          </v-col>
          <v-col class="d-flex justify-start justify-sm-center justify-md-center justify-lg-center justify-xl-center align-center">
            <h3>电话：</h3>
            <span class="contact-info-typography ps-1">023-62461003</span>
          </v-col>
          <v-col class="d-flex justify-start justify-sm-center justify-md-center justify-lg-center justify-xl-center align-center">
            <h3>邮编</h3>
            <span class="contact-info-typography ps-1">
              400065</span
            >
          </v-col>
        </v-col>
      </v-col>
      <v-col class="text-center white--text col-sm-12 col-12 col-md-6">
        <h2>联系我们</h2>
        <v-form ref="form">
          <v-text-field label="姓名" required class="white--text" dark></v-text-field>

          <v-text-field label="电子邮件" required dark></v-text-field>

          <v-textarea
            solo
            name="input-7-4"
            label="留言"
            background-color="#212121"
            dark
          ></v-textarea>

          <v-btn color="contact-info-button" class="mr-4">
            Submit
          </v-btn>
        </v-form>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "ContactContainer",
};
</script>

<style lang="scss" scoped>
$contact-container-text-color: #6495ed;

.contact-info {
  &-typography {
    color: $contact-container-text-color;
  }

  &-button {
    background-color: $contact-container-text-color !important;
    color: #fff;
  }
}
</style>
