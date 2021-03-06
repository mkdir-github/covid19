<template>
  <div class="About">
    <h2 class="About-Heading">
      当サイトについて
    </h2>
    <TextCard>
      当サイトは新型コロナウイルス感染症（COVID-19）に関する最新情報を提供するために、大阪府が
      <a href="https://code4.osaka" target="_blank" rel="noopener"
        >Code for OSAKA</a
      >の協力を得て開設したものです。
      <br />
      <br />
      大阪府による公式情報と客観的な数値をわかりやすく伝えることで、大阪府にお住まいの方や、大阪府内に拠点を持つ企業の方、大阪府を訪れる方が、現状を把握して適切な対策を取れるようにすることを目的としています。
    </TextCard>
    <TextCard title="ブラウザ環境について">
      当サイトは以下の環境でご覧いただくことを推奨いたします。<br />
      <ul class="About-Browser-List">
        <li>Microsoft Edge 最新版</li>
        <li>Mozilla Firefox 最新版</li>
        <li>Google Chrome 最新版 (Windows 10以上)</li>
        <li>Safari (macOS) 最新版</li>
        <li>Opera 最新版</li>
      </ul>
      ※
      推奨環境以外で利用された場合や、推奨環境下でもご利用のブラウザの設定等によっては、正しく表示されない場合がありますのでご了承ください。
    </TextCard>
    <TextCard title="当サイトへのリンクについて">
      当サイトへのリンクは自由です。
    </TextCard>
    <TextCard title="JavaScriptについて">
      当サイトではJavaScriptを使用しております。<br />
      JavaScriptを無効にして使用された場合、各ページが正常に動作しない、または、表示されない場合がございます。<br />
      当サイトをご利用の際には、JavaScriptを有効にして頂きますようお願いいたします。
    </TextCard>
    <TextCard title="クッキー (Cookie) について">
      当サイトの一部ではクッキーを使用しています。<br />
      クッキーとは、Webコンテンツからの要求で利用者の手元の端末に一時的に保存されるデータのことで、当サイトでは利用状況の把握のためにクッキーを使用する場合があります。<br />
      <br />
      ブラウザに関する情報の収集を希望しない場合は、インターネット閲覧ソフト（ブラウザ）をご自身で設定することにより、クッキーの機能が働かないようにすることも可能です。<br />
      <br />
      ただし、クッキーを受け入れない設定をされている場合は、当サイトの機能が正常に動作しない場合がございます。
    </TextCard>
    <TextCard title="Google Analyticsの利用について">
      当サイトでは、サービス向上やWebサイトの改善のためにGoogleの提供するアクセス分析のツールであるGoogle
      Analyticsを利用した計測を行っております。<br />
      Google
      Analyticsは、当サイトが発行するクッキー(Cookie)を利用して、個人を特定する情報を含まずにWebサイトの利用データ（アクセス状況、トラフィック、閲覧環境など）を収集しております。クッキー(Cookie)の利用に関してはGoogleのプライバシーポリシーと規約に基づいております。<br />
      取得したデータはWebサイト利用状況の分析、サイト運営者へのレポートの作成、その他のサービスの提供に関わる目的に限り、これを使用します。<br />
      <br />
      Google
      Analyticsの利用規約及びプライバシーポリシーに関する説明については、Google
      Analyticsのサイトをご覧ください。<br />
      <ul>
        <li>
          <a
            href="https://marketingplatform.google.com/about/analytics/terms/jp"
            target="_blank"
            rel="noopener"
          >
            Google Analytics利用規約
          </a>
        </li>
        <li>
          <a
            href="https://policies.google.com/privacy?hl=ja"
            target="_blank"
            rel="noopener"
          >
            Googleのプライバシーポリシー
          </a>
        </li>
        <li>
          <a
            href="https://support.google.com/analytics/answer/6004245"
            target="_blank"
            rel="noopener"
          >
            Google Analyticsに関する詳細情報
          </a>
        </li>
      </ul>
    </TextCard>
    <TextCard title="免責事項">
      当サイトに掲載されている情報の正確性については万全を期していますが、大阪府は利用者が当サイトの情報を用いて行う一切の行為について責任を負うものではありません。<br />
      <br />
      また、利用者が当サイトを利用したことにより発生した利用者の損害及び利用者が第三者に与えた損害に対して、責任を負うものではありません。<br />
      <br />
      当サイトに掲載されている情報は、予告なしに変更又は削除することがあります。
    </TextCard>
    <TextCard title="データについて">
      本サイトで公表している元データは、大阪府ホームページ「<a
        href="http://www.pref.osaka.lg.jp/iryo/osakakansensho/corona.html"
        target="_blank"
        rel="noopener"
        >新型コロナウイルス感染症について」</a
      >で公表しています。
    </TextCard>
    <TextCard title="ソースコードについて">
      本サイトのソースコードはMITライセンスで公開されており、誰でも自由に利用することができます。詳しくは、<a
        href="https://github.com/codeforosaka/covid19"
        target="_blank"
        rel="noopener"
        >GitHub リポジトリ</a
      >をご確認ください。
    </TextCard>

    <TextCard title="お問い合わせ先">
      <li>
        「<a
          href="http://www.pref.osaka.lg.jp/iryo/osakakansensho/corona-denwa.html"
          target="_blank"
          rel="noopener"
          >新型コロナウイルス感染症の発生に伴う電話相談窓口について</a
        >」
      </li>
      大阪府では、府民からの健康相談に応えるため、専用の府民相談窓口を設置しています。<br />
      また、新型コロナウイルス感染症に感染が疑われる方を対象に、府内各保健所に、新型コロナ受診相談センター（帰国者・接触者相談センター）を設置しています。詳しくは上記リンクより案内をご覧下さい。
      <br /><br />
      <li>
        「<a
          href="http://www.pref.osaka.lg.jp/it-suishin/sc/index.html#3"
          target="_blank"
          rel="noopener"
          >本サイトの構築に関するお問い合わせについて</a
        >」
      </li>
      本サイトの構築に関することについては、大阪府総務部スマートシティ戦略準備室にお問い合わせください。<br />
    </TextCard>
  </div>
</template>

<script lang="ts">
import TextCard from '@/components/TextCard.vue'

export default {
  components: {
    TextCard
  },
  head() {
    return {
      title: '当サイトについて'
    }
  }
}
</script>

<style lang="scss">
.About {
  &-Heading {
    @include font-size(30);
    font-weight: normal;
    color: $gray-2;
    margin-bottom: 12px;
  }
  & &-Browser-List {
    // セレクタ指定が&-Browser-List のみだと
    // .v-application ul の設定が勝ってしまい padding-left が24px となってしまうため
    // このようなセレクタ指定としています
    list-style: none;
    padding: 12px 0;
  }
}

a {
  @include text-link();
}
</style>
