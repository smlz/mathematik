<style>
@media print {
    hr {page-break-after: always;}
}
@media screen {
  hr {
    margin-bottom: 1000px !important;
  }
}
@media all {
  body, body > div.markdown-preview {
    padding: 0 ! important;
    margin: 0 ! important;
    width: 100% !important;
  }
  p {
    padding-bottom: 10px;
  }
  h1, h2, h3 {
    margin-top: 0 !important;
  }
  ol li f2 {
      display: inline-block;
      width: 49.5%;
  }
  ol li f3 {
      display: inline-block;
      width: 33%;
  }
  ol li f4 {
      display: inline-block;
      width: 24.75%;
  }
  ol li f5 {
      display: inline-block;
      width: 19.8%;
  }
  ol li f6 {
    display: inline-block;
    width: 16.5%;
  }
  ol {
      margin: 0 0 0 0;
      padding-left: 0 !important;
      counter-reset: item;
  }
  ol li {
      margin: 5px 0;
      padding-left: 0em;
      text-indent: 0em;
      list-style-type: none;
      counter-increment: item;

  }
  ol li > p {
      display: inline-block;
      vertical-align: top;
      width: 92%;
  }
  ol > li:before {
      display: inline-block;
      width: 1.5em;
      padding-right: 0em;
      margin-left: 0em;
      font-weight: bold;
      text-align: left;
      content: counter(item);
  }
  .katex-display {
    display: inline-block;
    margin: 5px 0;
  }
  .katex {
    font-size: 13.5pt;
  }
}
</style>
