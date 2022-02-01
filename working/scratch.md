<div class="footer">
  {{ if .PrevInSection }}
  <a href=" {{ .PrevInSection.Permalink }} ">Prev</a>
  {{ end }}
  {{ if and .PrevInSection .NextInSection }} | {{ end }}
  {{ if .NextInSection }}
  <a href=" {{ .NextInSection.Permalink }} "> Next </a>
  {{ end }}

</div>


On the relative / absolute / local vs. not - I don't know
what happens when you change the main.scss -- right now, it's a really long
link to a css on github. But somehow I don't know if it will notice changes
to the styles if you do it locally. If it's not, try again going local. 

Make sure to use the sub-root for anything with links that I make un-programmatically. 
Also that any images, etc. are linked off of /dataj/....


Found the addDate function and found out how to make a simple comparison for range. It's very confusing language! 

Github PAT: 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
