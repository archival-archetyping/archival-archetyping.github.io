---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: single
header:
  image: /assets/images/the-morandi-room.jpg
permalink: /
---
<style type="text/css">

* { box-sizing: border-box; }

html { /* apply a natural box layout model to all elements */ box-sizing: border-box; background-color: #fff; font-size: 14px; -webkit-text-size-adjust: 100%; -ms-text-size-adjust: 100%; }
@media (min-width: 48em) { html { font-size: 14px; } }
@media (min-width: 64em) { html { font-size: 16px; } }
@media (min-width: 80em) { html { font-size: 18px; } }

</style>

<!-- from here -->
## お知らせ - Information

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
