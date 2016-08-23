project_path: /web/_project.yaml
book_path: /web/shows/_book.yaml

{# wf_autogenerated #}


# {{title}} {: .page-title }

{{#each shows}}
## {{snippet.title}}

<a href="/web/{{path}}">
  <img class="attempt-right" src="{{snippet.thumbnails.medium.url}}">
</a>

{{ellipsis snippet.description 500}}

{{moment snippet.publishedAt "dddd, MMMM Do YYYY, h:mm a"}}

[Watch now](/web/{{path}}) 

<div style="clear:both;"></div>
{{/each}}