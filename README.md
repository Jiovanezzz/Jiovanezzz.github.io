# Jiovanezzz.github.io
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge"/>
    <title>Redmine</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Redmine" />
    <meta name="keywords" content="issue,bug,tracker" />
    <meta name="csrf-param" content="authenticity_token" />
    <meta name="csrf-token" content="NwbjiKebRGEvSy4iiiHzullqgH/Eg+8Zykv+e0g1mGHZdAL8vbPTzXaE59lifmDy1O0teqHvv+mPXb/3tM6emQ==" />
    
    <!-- Favicon -->
    <link rel='shortcut icon' href='images/favicon.ico' />

    <!-- CSS Stylesheets -->
    <link rel="stylesheet" media="all" href="css/jquery-ui-1.13.2.css" />
    <link rel="stylesheet" media="all" href="css/tribute-5.1.3.css" />
    <link rel="stylesheet" media="all" href="css/application.css" />
    <link rel="stylesheet" media="all" href="css/responsive.css" />

    <!-- JavaScript Files -->
    <script src="js/jquery-3.6.1-ui-1.13.2-ujs-6.1.7.js"></script>
    <script src="js/tribute-5.1.3.min.js"></script>
    <script src="js/tablesort-5.2.1.min.js"></script>
    <script src="js/tablesort-5.2.1.number.min.js"></script>
    <script src="js/application.js"></script>
    <script src="js/responsive.js"></script>

    <script>
    //<![CDATA[
    $(window).on('load', function(){ 
        warnLeavingUnsaved('A página atual contém texto que não foi salvo e será perdido se você sair desta página.');
    });
    //]]>
    </script>

    <script>
    //<![CDATA[
    rm = window.rm || {};
    rm.AutoComplete = rm.AutoComplete || {};
    rm.AutoComplete.dataSources = JSON.parse('{"issues":"/redmine23/issues/auto_complete?q=","wiki_pages":"/redmine23/wiki_pages/auto_complete?q="}');
    //]]>
    </script>

    <!-- Atom Feeds -->
    <link rel="alternate" type="application/atom+xml" title="Redmine: Últimas notícias" href="news.atom" />
    <link rel="alternate" type="application/atom+xml" title="Redmine: Atividade" href="activity.atom" />
</head>

<body class="controller-welcome action-index avatars-off">

    <div id="wrapper">

        <div class="flyout-menu js-flyout-menu">
            <div class="flyout-menu__search">
                <form action="/redmine23/search" accept-charset="UTF-8" name="form-cf0a9a6e" method="get">
                    <input name="utf8" type="hidden" value="&#x2713;" autocomplete="off" />
                    <label class="search-magnifier search-magnifier--flyout" for="flyout-search">&#9906;</label>
                    <input type="text" name="q" id="flyout-search" class="small js-search-input" placeholder="Busca" />
                </form>
            </div>
            <div class="flyout-menu__avatar flyout-menu__avatar--no-avatar">
                <a class="user active" href="/redmine23/users/1">admin</a>
            </div>
            <h3>Geral</h3>
            <span class="js-general-menu"></span>
            <span class="js-sidebar flyout-menu__sidebar"></span>
            <h3>Perfil</h3>
            <span class="js-profile-menu"></span>
        </div>

        <div id="top-menu">
            <div id="account">
                <ul>
                    <li><a class="my-account" href="/redmine23/my/account">Minha conta</a></li>
                    <li><a class="logout" rel="nofollow" data-method="post" href="/redmine23/logout">Sair</a></li>
                </ul>
            </div>
            <div id="loggedas">Acessando como: <a class="user active" href="/redmine23/users/1">admin</a></div>
            <ul>
                <li><a class="home" href="/redmine23/">Página inicial</a></li>
                <li><a class="my-page" href="/redmine23/my/page">Minha página</a></li>
                <li><a class="projects" href="/redmine23/projects">Projetos</a></li>
                <li><a class="administration" href="/redmine23/admin">Administração</a></li>
                <li><a target="_blank" rel="noopener" class="help" href="https://www.redmine.org/guide">Ajuda</a></li>
            </ul>
        </div>

        <div id="header">
            <a href="#" class="mobile-toggle-button js-flyout-menu-toggle-button"></a>
            <div id="quick-search">
                <form action="/redmine23/search" accept-charset="UTF-8" name="form-4494eb30" method="get">
                    <input name="utf8" type="hidden" value="&#x2713;" autocomplete="off" />
                    <input type="hidden" name="scope" autocomplete="off" />
                    <label for='q'>
                        <a accesskey="4" href="/redmine23/search">Busca</a>:
                    </label>
                    <input type="text" name="q" id="q" size="20" class="small" accesskey="f" data-auto-complete="true" />
                </form>
            </div>
            <h1>Redmine</h1>
        </div>

        <div id="main" class="nosidebar">
            <div id="content">
                <h2>Página inicial</h2>
                <div class="splitcontent">
                    <div class="splitcontentleft">
                        <div class="wiki"></div>
                    </div>
                    <div class="splitcontentright"></div>
                </div>
                <div style="clear:both;"></div>
            </div>
        </div>

        <div id="footer">
            Powered by <a target="_blank" rel="noopener" href="https://www.redmine.org/">Redmine</a> &copy; 2006-2022 Jean-Philippe Lang
        </div>

        <div id="ajax-indicator" style="display:none;"><span>Carregando...</span></div>
        <div id="ajax-modal" style="display:none;"></div>

    </div>

</body>
</html>
