---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
header:
  image: /assets/images/the-morandi-room.jpg
permalink: /
---

<!-- from here -->
## お知らせ - Information

2021.03.18
: 2021年3月31日の9時より21時まで、イベント「[メタ・モ（ニュ）メント2021](/meta-mo-nu-ment-2021/)」を開催します。
: We will hold an event, "[Meta mo(nu)ment 2021](/meta-mo-nu-ment-2021/)" from 9:00 to 21:00 on March 31, 2021.

2021.02.23
: 2021年2月20日より23日まで、情報科学芸術大学院大学［IAMAS］が開催する展覧会「[IAMAS 2021](https://www.iamas.ac.jp/exhibit21/)」にて、展覧会内展覧会「[Archival Archetyping Exhibition in IAMAS 2021](/iamas-2021/)」を開催しました。
: We held an intra-exhibition exhibition, "Archival Archetyping Exhibition in IAMAS 2021" at the exhibition "[IAMAS 2021](https://www.iamas.ac.jp/exhibit21/)" held by the Institute of Advanced Media Arts and Sciences [IAMAS](/iamas-2021/) from February 20 to 23, 2021.

2021.01.11
: 2020年12月24日より2021年1月10日まで、展覧会「[Archival Archetyping Exhibition 2020](/exhibition-2020/)」を開催しました。展覧会に関連して開催したトークイベントの記録と、展覧会レポートを公開しております。
: We held the [Archival Archetyping Exhibition 2020]((/exhibition-2020/)) from December 24, 2020, to January 10, 2021. Records of the talk event held in association with the exhibition and the exhibition report are available.

2020.06.09
: 人工知能学会第34回全国大会国際セッションにおいて「[モランディの部屋](https://www.jstage.jst.go.jp/article/pjsai/JSAI2020/0/JSAI2020_1G3ES504/_article/-char/ja/){: .outbound}」を発表しました。
: We presented "[The Morandi Room](https://www.jstage.jst.go.jp/article/pjsai/JSAI2020/0/JSAI2020_1G3ES504/_article/-char/en/){: .outbound}" at the International Session of the 34th Annual Conference of the Japanese Society for Artificial Intelligence.

<script>
function trackOutboundLink(event) {
  console.log(event.target.textContent);
  gtag('event', 'click', {
    event_category: 'outbound',
    event_label: event.target.textContent + ' ⇢ ' + event.target.href,
    transport_type: 'beacon',
    event_callback: function () {
      document.location = event.target.href;
    },
  });
}

document.querySelectorAll('a.outbound').forEach((item) => {
  item.addEventListener('click', trackOutboundLink);
});
</script>
