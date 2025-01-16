<head>
     <style type="text/css">
            #content {
                background-color: #fff;
                color: #000;
            }

            {CustomCSS}
        </style>
        {MobileAppHeaders}
        <meta charset="utf-8">
        <title>{Title}{block:TagPage} ({lang:Posts tagged Tag}){/block:TagPage}{block:SearchPage} ({lang:Search results for SearchQuery}){/block:SearchPage}{block:PermalinkPage}{block:PostSummary} — {PostSummary}{/block:PostSummary}{/block:PermalinkPage}</title>
        <meta name="description" content="{MetaDescription}">
        {block:Hidden}
        <meta name="if:Sliding header" content="1">
        <meta name="if:Show navigation" content="1">
        <meta name="if:Endless scrolling" content="1">
        <meta name="if:Lazy image loading" content="0">
        <meta name="if:Syntax highlighting" content="0">
        <meta name="select:Layout" content="regular" title="Regular">
        <meta name="select:Layout" content="narrow" title="Minimal">
        <meta name="select:Layout" content="wide" title="Wide">
        <meta name="select:Layout" content="grid" title="Grid">
        <meta name="if:Related Posts" content="1">
        <meta name="if:Show Twitter link" content="0">
        <meta name="text:Disqus shortname" content="">
        <meta name="text:Google analytics ID" content="">
        {/block:Hidden}

        <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
        <meta name="theme-color" content="#35465D">
        <link rel="shortcut icon" href="{Favicon}">
        <link rel="apple-touch-icon-precomposed" href="{PortraitURL-128}">
        <link rel="alternate" type="application/rss+xml" href="{RSS}">
        <link rel="stylesheet" href="https://assets.tumblr.com/default-theme/r1/main-min.css">
        {block:IfSyntaxHighlighting}
        <link rel="stylesheet" href="https://static.tumblr.com/ehm1tdz/2VWnye81h/tumblr-highlightjs.css">
        {/block:IfSyntaxHighlighting}
  <script src="//pull.cappuccicons.com/cpf.js"></script>
  <script src="https://kit.fontawesome.com/3de2e96a1c.js" crossorigin="anonymous"></script>
</head>
<style>
@font-face { font-family: 'Calora'; font-style: normal; src: url('https://dl.dropbox.com/scl/fi/xmryurenbmswh8468pd4g/calora.otf?rlkey=4nf733828vhv38nhn1vgqsqy4&st=lnzw5dph&dl=0'); format('truetype'); }
@font-face { font-family: 'Against'; font-style: normal; src: url('https://dl.dropbox.com/scl/fi/zapkujv120p1s79colzee/against-regular.otf?rlkey=rpb3k4brqajjxps2nb1yl5tmx&st=khreca6a&dl=0'); format('truetype'); }
    :root{
  /*Colores Principal*/
    --r1: #a0c8cd;
    --r2: #86b3b9;
    --r3: #455e61;
    --r4: #ffffff;
  /*Colores Neutros*/
    --n1: #567c81;
    --n2: #578a91;
    --n3: #dfdfdf;
    --n4: #000;
  /*Fonts*/
--font1:'Calora';
--font2:'against';
--font3:'Calibri';
/*Backgrounds*/
--bg1:url(https://i.ibb.co/5r5VQqm/fondoblanco.png);
--bg2:url(https://i.ibb.co/7VV5Lgn/fondonegro.png);
}
::-webkit-scrollbar {
    width: 8px;
}
::-webkit-scrollbar-thumb {
    background: #FF8195;
    border: 1px solid var(--n2);
    border-radius:10px;
}
::-webkit-scrollbar-track {
    border: 3px solid var(--n1);
    border-radius:10px;
}
body {
    padding: 0;
    margin: 0;
    background: var(--bg1);
    background-attachment: fixed;
}
#navegador-GD {
    position: fixed;
    left: 0;
    top: 0;
    padding: 10px;
    background: var(--r1);
    width: 15%;
    height: 100%;
    border-right: 1px solid var(--n4);
}
#navegador-opcion {
    position: fixed;
    display: grid;
    justify-content: center;
    align-items: center;
    padding: 10px;
    background: var(--r2);
    left: 16%;
    top: 0;
    width: 3%;
    height: 100%;
    box-sizing: border-box;
}
.Avatar {
    margin: 10px;
    background: var(--n1);
    overflow: hidden;
    position: relative;
    padding: 20px;
    box-sizing: border-box;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 180px;
    border-radius: 100px;
}
.Avatar img {
    width: 80%;
    height: auto;
    filter: grayscale(1);
}
.Title-GD {
    font-size: 25px;
    line-height: 0.8em;
    font-family: var(--font1);
    text-align: center;
    color: var(--r3);
}
.Title-GD .cp {
    background: var(--r4);
    width: 20%;
    padding: 10px;
    border-radius: 100px;
    border: 15px solid var(--r1);
    margin-top: -30%;
    position: relative;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.Title-GD span {
    font-size: 12px;
    font-family: var(--font3);
    display: block;
    line-height: 1em;
    margin: 8px;
    background: var(--r2);
    padding: 10px;
    border-radius: 10px;
    font-weight: bold;
    color: var(--r4);
    text-align: justify;
    border: 1px solid var(--r4);
}
.menu-visitor a {
    font-size: 10px;
    font-family: var(--font3);
    text-decoration: none;
    width: 48%;
    display: inline-block;
    color: var(--n1);
    font-weight: bold;
}
.menu-visitor .cp {
    color: var(--r4);
    margin-right: 5px;
    font-size: 15px;
    float: left;
}
#navegador-opcion .cp,#navegador-opcion a {
    color: var(--r4);
    text-decoration: none;
}
.contenedor-GD {
    margin: 5% 25%;
    width: 47%;
    background: #fff8;
    padding: 10px;
    border-radius: 10px;
    border: 1px solid var(--r4);
}
.opcion {
    background: var(--r4);
    position: fixed;
    right: 0;
    top: 20%;
    margin-right: 2%;
    width: 20%;
    height: 75%;
    border-radius: 20px;
    padding: 10px;
    box-sizing: border-box;
    border: 1px solid var(--r3);
    text-align:center;
}
#posts {
    margin: 0 !important;
    padding: 0px;
    color:var(--r4);
}
.post {
    border: 1px solid var(--r4);
    padding: 50px;
    box-sizing: border-box;
    border-radius: 10px;
    background: var(--r2);
    margin-bottom: 10px;
}
.reblog-header {
    background: var(--r4);
    padding: 10px;
    border-radius: 10px;
    box-shadow: -6px -5px 0px var(--r1);
    display: flex
    align-items: center;
    font-family: var(--font2);
    font-size: 14px;
    margin-top:20px;
}
.reblog-header img {
    border-radius: 10px;
    filter: grayscale(1);
    border: 1px solid var(--n2);
}
.reblog-header a {
    margin: 10px;
    color: var(--r3);
    text-decoration: none;
    font-size: 20px;
    text-transform: capitalize;
}
.reblog-header span {
    font-size: 10px;
    font-family: var(--font3);
    color: var(--n2);
    padding: 10px;
    background: var(--r1);
    border-radius: 20px;
}
.reblog-body {
    width: 100%;
    overflow: hidden;
    box-sizing: border-box;
    font-family: var(--font3);
    color: var(--r4);
    font-weight: bold;
    background: var(--n2);
    margin: 10px;
    border-radius: 10px;
    margin-left: -5px;
}
span.npf_color_rachel {
    padding: 10px;
    background: var(--r4);
    border-radius: 10px;
    font-size: 8px;
    color: var(--n2);
    text-transform: uppercase;
    letter-spacing: 3px;
}
ul.like_and_reblog_buttons {
    display: flex;
    padding: 10px;
    align-items: center;
}
ul.like_and_reblog_buttons li {
    display: block;
    padding: 10px;
    margin: 10px;
    background: var(--r4);
    border-radius: 10px;
}
ul.like_and_reblog_buttons a {
    font-size: 10px;
    font-family: var(--font3);
    color: var(--n2);
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 3px;
}
ul.tags {
    background: var(--r1);
    padding: 10px;
    margin: 0;
    margin-top: -50px;
    border-radius: 10px;
    border: 1px solid var(--r4);
}
ul.tags li {
    display: inline;
    margin: 5px;
}
ul.tags a {
    color: var(--r2);
    text-decoration: none;
    display: inline-block;
    padding: 2px;
    margin-top: 10px;
    font-size: 11px;
}
#posts h1 {
    color: var(--r4) !important;
    font-family: var(--font2);
    font-style: normal !important;
    background: var(--r1);
    padding: 10px;
    letter-spacing: 2px;
    margin: 10px;
    border-radius: 20px;
    text-align: center;
}
#posts h1 span {
    color: var var(--r4);
    text-align: center;
    display: grid;
    line-height: 1em;
}
#posts h1 small {
    color: var(--n1);
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: 12px;
}
#posts h2 {
    color: var(--r4);
    font-family: var(--font1);
    text-transform: uppercase;
    font-size: 40px;
    border-bottom: 1px solid;
}
span.npf_color_ross {
    color: var(--r4);
    padding: 10px;
    border: 1px solid;
    display: block;
    border-radius: 20px;
    background: var(--r3);
    font-family: var(--font3);
    margin: 10px;
}
h2 span.npf_color_monica {
    color: var(--r3);
    margin-left: 10px;
    letter-spacing: 10px;
    background: var(--r4);
    padding: 10px;
    border-radius: 20px;
    font-size: 10px;
    position: relative;
    top: -12px;
    margin-right: 20px;
}
#posts h1 span.npf_color_monica,#posts h1 span.npf_color_niles {
    display: contents;
    color: var(--r2);
    letter-spacing: 10px;
}
blockquote.npf_indented {
    background: var(--n2);
    margin: 10px;
    box-sizing: border-box;
    padding: 10px;
    border-radius: 10px;
    margin-top: 10px;
    border: 1px solid var(--r4);
}
blockquote.npf_indented a {
    text-decoration: none;
    color: var(--r4);
    padding: 10px;
    border-radius: 20px;
}
.post.answer {
    background: var(--r1);
    color: var(--r3);
    line-height: 1em;
    font-family: var(--font3);
}
p.headerask {
    background: var(--r2);
    width: 50%;
    padding: 10px;
    font-family: var(--font2);
    text-align: center;
    color: var(--r4) !important;
    border-radius: 20px;
    border: 1px solid;
    display: flex;
    justify-content: center;
    align-items: center;
}
p.headerask a {
    color: var(--r4);
    text-decoration: none;
}
p.headerask img {
    border-radius: 10px;
    margin: 5px;
    border: 1px solid var(--r4);
}
ol.notes {
    background: var(--n2);
    padding: 20px 50px;
    box-sizing: border-box;
    border-radius: 20px;
    font-size: 10px;
    font-family: var(--font3);
}
ol.notes li {
    padding: 5px;
    margin: 4px;
}
ol.notes a {
    text-decoration: none;
    color: var(--r4);
    font-weight: bold;
    font-family: var(--font2);
    font-size: 12px;
}
.opcion span {
    display: block;
    font-family: var(--font1);
    text-transform: uppercase;
    padding: 10px;
    font-size: 20px;
    text-align: center;
    color: var(--n2);
    letter-spacing: 3px;
    border-bottom: 1px solid;
    line-height: 1em;
    margin-bottom: 10px;
}
repli,resp {
    display: block;
    background: var(--r2);
    padding: 10px;
    margin-left: 10px;
    border-radius: 20px;
    color: var(--r4);
    line-height: 1em;
    box-shadow: -10px -10px 0px var(--r4);
    font-size: 12px;
}
repli img {
    float: left;
    padding: 10px;
    margin: 10px;
    border-radius: 10px;
    background: var(--n2);
    border: 1px solid var(--r4);
}
.credit-gg {
    position: fixed;
    top: 0;
    right: 0;
    margin-top: 5.5%;
    margin-right: 3.7%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.credit-gg a {
    text-decoration: none;
    font-family: var(--font1);
    background: var(--r2);
    color: var(--r4);
    padding: 10px;
    border-radius: 20px;
    letter-spacing: 2px;
}
.credit-gg .cp {
    display: inline-block;
    padding: 10px;
    background: var(--r4);
    color: var(--r2);
    border-radius: 20px;
    font-size: 20px;
    margin-right: 10px;
}
</style>
<script>
  // Estado inicial: modo predeterminado
let isNeutralMode = false;

function toggleMode() {
  if (isNeutralMode) {
    // Regresar a los colores predeterminados eliminando las propiedades CSS en línea
    document.documentElement.style.removeProperty('--n1');
    document.documentElement.style.removeProperty('--n2');
    document.documentElement.style.removeProperty('--n3');
    document.documentElement.style.removeProperty('--n4');
    document.body.style.removeProperty('background');
  } else {
    // Cambiar a colores negros
    document.documentElement.style.setProperty('--n1', '#fff');
    document.documentElement.style.setProperty('--n2', '#9d9d9d');
    document.documentElement.style.setProperty('--n3', '#000');
    document.documentElement.style.setProperty('--n4', '#000');
    document.body.style.background = 'var(--bg2)'; // Fondo alternativo (imagen)
  }

  // Alternar el estado
  isNeutralMode = !isNeutralMode;
}
</script>
<script>
 // Estado inicial: colores "fire"
let isFireMode = false;

function toggleFireMode() {
  if (isFireMode) {
    // Restaurar colores predeterminados eliminando los valores personalizados
    document.documentElement.style.removeProperty('--r1');
    document.documentElement.style.removeProperty('--r2');
    document.documentElement.style.removeProperty('--r3');
    document.documentElement.style.removeProperty('--r4');
  } else {
    // Cambiar a colores azules
    document.documentElement.style.setProperty('--r1', '#131763');
    document.documentElement.style.setProperty('--r2', '#8f92a7');
    document.documentElement.style.setProperty('--r3', '#5374dd');
    document.documentElement.style.setProperty('--r4', '#061047');
  }

  // Alternar el estado
  isFireMode = !isFireMode;
}

</script>
<div id="navegador-GD">
<div class="Avatar">
<img src="{PortraitURL-128}" class="pfdynamite"/>
</div>
<div class="Title-GD">
<center><i class="cp cp-candy"></i></center>
{TITLE}
<span>{Description}</span>
<span>La skin de este blog fue realizado por Gummies Dynamite,tambien se realiza merito especial a: Cappuccicons, Dafont, Freepik</span>
</div>
<div class="menu-visitor">
<a href="/archive"><i class="cp cp-candy"></i>
                Archivo</a>
<a href="/" target="_blank"><i class="cp cp-candy"></i>
                Link</a>
<a href="/" target="_blank"><i class="cp cp-candy"></i>
                Link</a>
<a href="/" target="_blank"><i class="cp cp-candy"></i>
                Link</a>
<a href="/" target="_blank"><i class="cp cp-candy"></i>
                Link</a>
<a href="/" target="_blank"><i class="cp cp-candy"></i>
                Link</a>                
</div>
</div>
<div id="navegador-opcion">
<a href="https://gummies-dynamite.tumblr.com/"><i class="fas fa-home"></i></a>
<a href="#" onclick="toggleMode()"><i class="cp cp-moon"></i></a>
<a href="#" onclick="toggleFireMode()"><i class="cp cp-fire"></i></a>
         {block:Pagination}
         {block:PreviousPage}
                <nextpre><a href="{PreviousPage}"><i class="cp cp-chevron-left"></i></a></nextpre>
            {/block:PreviousPage}
            {block:NextPage}
               <nextpre><a href="{NextPage}"><i class="cp cp-chevron-right
"></i></a></nextpre>
            {/block:NextPage}{/block:Pagination}
</div>
<div class="contenedor-GD">
  <ol id="posts">
    <div id="posts">
      {block:Posts}
        {block:Text}
          <div class="post text">
            {block:NotReblog}
              {Body}
            {/block:NotReblog}
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
            {block:HasTags}
              <ul class="tags">
                {block:Tags}
                  <li>
                    <a href="{TagURL}">#{Tag}</a>
                  </li>
                {/block:Tags}
              </ul>
            {/block:HasTags}
          </div>
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Text}
        {block:Answer}
          <div class="post answer">
            <p class="headerask"><img src="{AskerPortraitURL-30}" class="pfdynamite"/>{Asker} Pregunta: </p>
            <quest>{Question}</quest>
            {block:Answerer}
              <resp>{Answer}</resp>
            {/block:Answerer}
            <!--Original Post-->
            {block:NotReblog}
              <repli><img src="{PortraitURL-30}" class="pfdynamite"/>{Replies}</repli>
            {/block:NotReblog}
            <!--Post is a reblog-->
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
            {block:HasTags}
              <ul class="tags">
                {block:Tags}
                  <li>
                    <a href="{TagURL}">#{Tag}</a>
                  </li>
                {/block:Tags}
              </ul>
            {/block:HasTags}
          </div>
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Answer}
        {block:Photo}
          <div class="post photo">
            <img src="{PhotoURL-500}" alt="{PhotoAlt}"/>
            <!--Original Post-->
            {block:NotReblog}
              {Caption}
            {/block:NotReblog}
            <!--Post is a reblog-->
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
            {block:HasTags}
              <ul class="tags">
                {block:Tags}
                  <li>
                    <a href="{TagURL}">#{Tag}</a>
                  </li>
                {/block:Tags}
              </ul>
            {/block:HasTags}
          </div>
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Photo}
        {block:Photoset}
          <div class="post photoset">
            {Photoset}
            <!--Original Post-->
            {block:NotReblog}
              {Caption}
            {/block:NotReblog}
            <!--Post is a reblog-->
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
            {block:HasTags}
              <ul class="tags">
                {block:Tags}
                  <li>
                    <a href="{TagURL}">#{Tag}</a>
                  </li>
                {/block:Tags}
              </ul>
            {/block:HasTags}
          </div>
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Photoset}
        {block:Quote}
          <div class="post quote">
            "{Quote}"
            {block:Source}
              <div class="source">{Source}</div>
            {/block:Source}
          </div>
        {/block:Quote}
        {block:Link}
          <div class="post link">
            <a href="{URL}" class="link" {Target}>{Name}</a>
            <!--Original Post-->
            {block:NotReblog}
              {Description}
            {/block:NotReblog}
            <!--Post is a reblog-->
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
            {block:HasTags}
              <ul class="tags">
                {block:Tags}
                  <li>
                    <a href="{TagURL}">#{Tag}</a>
                  </li>
                {/block:Tags}
              </ul>
            {/block:HasTags}
          </div>
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Link}
        {block:Chat}
          <div class="post chat">
            {block:Title}
              <h3><a href="{Permalink}">{Title}</a></h3>
            {/block:Title}

            <ul class="chat">
              {block:Lines}
                <li class="{Alt} user_{UserNumber}">
                  {block:Label}
                    <span class="label">{Label}</span>
                  {/block:Label}{Line}
                </li>
              {/block:Lines}
            </ul>
          </div>
        {/block:Chat}
        {block:Video}
          <div class="post video">
            {Video-700}
            {block:NotReblog}
              {Description}
            {/block:NotReblog}
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
            {block:HasTags}
              <ul class="tags">
                {block:Tags}
                  <li>
                    <a href="{TagURL}">#{Tag}</a>
                  </li>
                {/block:Tags}
              </ul>
            {/block:HasTags}
          </div>
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Video}
        {block:Audio}
          <div class="post audio">
            {AudioEmbed}
            <!--Original Post-->
            {block:NotReblog}
              {Description}
            {/block:NotReblog}
            <!--Post is a reblog-->
            {block:RebloggedFrom}
              <div class="reblog-list">
                {block:Reblogs}
                  <div class="reblog-header">
                    {block:IsActive}
                      <img src="{PortraitURL-64}" class="reblog"/><a href="{Permalink}">{Username}</a><span>{BLOCK:DATE}{DAYOFMONTHWITHZERO} / {MONTH} / {YEAR} - {24HOUR}:{MINUTES}:{CAPITALAMPM}{/BLOCK:DATE}</span>
                    {/block:IsActive}
                    {block:IsDeactivated}
                      <span>{Username}</span>
                    {/block:IsDeactivated}
                  </div>
                  <div class="reblog-body">{Body}</div>
                {/block:Reblogs}
              </div>
            {/block:RebloggedFrom}
            <ul class="like_and_reblog_buttons">
              <li>{ReblogButton}</li>
              <li>{LikeButton}</li>
              <li><note>{block:NoteCount}<a href="{Permalink}">{NoteCountWithLabel}</a>{/block:NoteCount}</note></li>
            </ul>
          </div>
          {block:HasTags}
            <ul class="tags">
              {block:Tags}
                <li>
                  <a href="{TagURL}">#{Tag}</a>
                </li>
              {/block:Tags}
            </ul>
          {/block:HasTags}
          {block:PostNotes}{PostNotes-16}{/block:PostNotes}
        {/block:Audio}
      {/block:Posts}
    </div>
  </ol>
</div>
<div class="credit-gg"><i class="cp cp-bomb"></i>
<a href="https://gummies-dynamite.tumblr.com/">Gummies Dynamite</a></div>
        <div class="opcion">
            <span>Contenido Especial</span>
             
        </div>
