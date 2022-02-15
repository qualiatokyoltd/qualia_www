<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-card>
        <v-card-title class="headline"> 会社概要 </v-card-title>
        <v-simple-table>
          <tbody>
            <tr><th>社名（法人名）</th><td>株式会社クオリア</td></tr>
            <tr><th>会社法人等番号</th><td>0100-01-162379</td></tr>
            <tr><th>所在地</th><td>東京都港区赤坂１－１２－３２</td></tr>
            <tr><th>事業内容</th><td>ヘルスケア支援システム開発</td></tr>
            <tr><th>設立</th><td>平成26年8月8日</td></tr>
            <tr><th>資本金の額</th><td>金3550万円</td></tr>
          </tbody>
        </v-simple-table>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'CompanyPage',
}
</script>
