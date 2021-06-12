<template>
  <body>
        <div class="header">
            <div class="header-logo">友紀歯科</div>
            <div class="header-list">
                <ul>
                    <li>施設情報</li>
                    <li>診療受付・休診日</li>
                    <li>アクセス</li>
                </ul>
            </div>
        </div>

        <div class="main">
            <div class="contents">
                <h1 class="section-title">施設情報</h1>
                <img src="https://pic1.homemate-research.com/pubuser1/pubuser_facility_img/5/0/0/24212300005/0000003195/24212300005_0000003195_1.jpg" alt="外観">
                <table>
                    <tr>
                        <th class="table-head">施設名</th>
                        <td class="table-data">友紀歯科医院</td>
                    </tr>
                    <tr>
                        <th class="table-head">診療科目</th>
                        <td class="table-data">歯科</td>
                    </tr>
                    <tr>
                        <th class="table-head">電話番号</th>
                        <td class="table-data">０５９７－８９－４６１８</td>
                    </tr>
                    <tr>
                        <th class="table-head">所在地</th>
                        <td class="table-data">〒５１９－４３２４　三重県熊野市井戸町７３５－２</td>
                    </tr>
                </table>
            </div>

            <div class="contents">
                <h1 class="section-title">診療受付・休診日</h1>
                <table>
                    <tr>
                        <th class="tabletime-head">時間</th>
                        <th class="tabletime-head">月</th>
                        <th class="tabletime-head">火</th>
                        <th class="tabletime-head">水</th>
                        <th class="tabletime-head">木</th>
                        <th class="tabletime-head">金</th>
                        <th class="tabletime-head">土</th>
                        <th class="tabletime-head">日</th>
                        <th class="tabletime-head">祝</th>
                    </tr>
                    <tr>
                        <td class="tabletime-data">9:00~12:00</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                    </tr>
                    <tr>
                        <td class="tabletime-data">14:00~18:00</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                    </tr>
                    <tr>
                        <td class="tabletime-data">14:30~19:30</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">●</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                        <td class="tabletime-data">―</td>
                    </tr>
                    <tr>
                        <td class="tabletime-info" colspan="9">
                            予約制・臨時休診あり
                        </td>
                    </tr>
                </table>
                <p class="coment">※新型コロナウイルス感染拡大により、診療時間・休診日等が記載と異なる場合がございますのでご注意下さい。</p>
            </div>

            <div class="contents">
                <h1 class="sectiontitle">アクセス</h1>
                <tr>
                    <th>交通手段</th>
                    <td>JR紀勢本線　熊野市駅</td>
                </tr>
                <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d13247.89172078296!2d136.097334!3d33.890351!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0xff1ab8702fb2b0c7!2z5Y-L57SA5q2v56eR5Yy76Zmi!5e0!3m2!1sja!2sjp!4v1623326619736!5m2!1sja!2sjp" 
                width="300" 
                height="200" 
                style="border:0;" 
                allowfullscreen="" 
                loading="lazy"></iframe>
            </div>
        </div>
    </body>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

