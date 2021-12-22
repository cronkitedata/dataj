<div class="footer">
  {{ if .PrevInSection }}
  <a href=" {{ .PrevInSection.Permalink }} ">Prev</a>
  {{ end }}
  {{ if and .PrevInSection .NextInSection }} | {{ end }}
  {{ if .NextInSection }}
  <a href=" {{ .NextInSection.Permalink }} "> Next </a>
  {{ end }}

</div>
