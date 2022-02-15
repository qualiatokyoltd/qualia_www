<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card>
        <v-card-title class="headline"> Welcome to Qualia Ltd. </v-card-title>
        <v-card-text>
          <p>
            For more information, check out the
            <a
              href="https://crowdlinks.jp/profiles/B80hgFFoRGgQzeAw296Ya9mBIlG3"
              target="_blank"
              rel="noopener noreferrer"
            >
              Crowdlinks </a
            >.
          </p>
          <p>
            会社概要はこちら
            <nuxt-link to="company"> Company Profile </nuxt-link>.
          </p>
          <p>
            check code on the github
            <a
              href="https://github.com/qualiatokyoltd"
              target="_blank"
              rel="noopener noreferrer"
              title="contribute"
            >
              github </a
            >.
          </p>
          <p>Thank you for developing with us.</p>
          <div class="text-xs-right">
            <em><small>&mdash; Hideyuki Katsushiro</small></em>
          </div>
        </v-card-text>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
