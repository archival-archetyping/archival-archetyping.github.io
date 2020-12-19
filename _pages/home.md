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

2020.12.17
: 2020年12月24日より展覧会を開催いたします。詳細は<a href="exhibition-2020/index.html" onclick="gtag('event', 'click', {'event_category': 'transition', 'event_label': 'home to exhibition 2020 (ja)', 'value': '1'});">こちら</a>よりご確認ください。
: We will hold an exhibition from December 24, 2020. For more information, please click <a href="exhibition-2020/index.html" onclick="gtag('event', 'click', {'event_category': 'transition', 'event_label': 'home to exhibition 2020 (en)', 'value': '1'});">here</a>.

2020.06.09
: 人工知能学会第34回全国大会国際セッションにおいて「<a class="outbound" href="https://www.jstage.jst.go.jp/article/pjsai/JSAI2020/0/JSAI2020_1G3ES504/_article/-char/ja/">モランディの部屋</a>」を発表しました。
: We presented "<a class="outbound" href="https://www.jstage.jst.go.jp/article/pjsai/JSAI2020/0/JSAI2020_1G3ES504/_article/-char/en/">The Morandi Room</a>" at the International Session of the 34th Annual Conference of the Japanese Society for Artificial Intelligence.

<script>
document.querySelector('a.outbound').addEventListener('click', function (event) {
  gtag('event', 'click', {
    event_category: 'outbound',
    event_label: event.currentTarget.textContent + ' ⇢ ' + event.currentTarget.href,
    transport_type: 'beacon',
    event_callback: function () {
      document.location = event.currentTarget.href;
    },
  });
});
</script>
