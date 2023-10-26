{"payload":{"allShortcutsEnabled":false,"fileTree":{"":{"items":[{"name":"api","path":"api","contentType":"directory"},{"name":".gitignore","path":".gitignore","contentType":"file"},{"name":"LICENSE","path":"LICENSE","contentType":"file"},{"name":"README.md","path":"README.md","contentType":"file"},{"name":"github.json","path":"github.json","contentType":"file"},{"name":"update.cmd","path":"update.cmd","contentType":"file"},{"name":"update.py","path":"update.py","contentType":"file"},{"name":"update.sh","path":"update.sh","contentType":"file"}],"totalCount":8}},"fileTreeProcessingTime":2.1198189999999997,"foldersToFetch":[],"reducedMotionEnabled":null,"repo":{"id":396446740,"defaultBranch":"master","name":"LineageOTAstatic","ownerLogin":"ADeadTrousers","currentUserCanPush":false,"isFork":false,"isEmpty":false,"createdAt":"2021-08-15T18:14:52.000Z","ownerAvatar":"https://avatars.githubusercontent.com/u/28513067?v=4","public":true,"private":false,"isOrgOwned":false},"symbolsExpanded":false,"treeExpanded":true,"refInfo":{"name":"master","listCacheKey":"v0:1629051908.584468","canEdit":false,"refType":"branch","currentOid":"a1b8560a93119d924a46728ab45bdcf821e4d360"},"path":"README.md","currentUser":null,"blob":{"rawLines":null,"stylingDirectives":null,"csv":null,"csvError":null,"dependabotInfo":{"showConfigurationBanner":false,"configFilePath":null,"networkDependabotPath":"/ADeadTrousers/LineageOTAstatic/network/updates","dismissConfigurationNoticePath":"/settings/dismiss-notice/dependabot_configuration_notice","configurationNoticeDismissed":null,"repoAlertsPath":"/ADeadTrousers/LineageOTAstatic/security/dependabot","repoSecurityAndAnalysisPath":"/ADeadTrousers/LineageOTAstatic/settings/security_analysis","repoOwnerIsOrg":false,"currentUserCanAdminRepo":false},"displayName":"README.md","displayUrl":"https://github.com/ADeadTrousers/LineageOTAstatic/blob/master/README.md?raw=true","headerInfo":{"blobSize":"5.43 KB","deleteInfo":{"deleteTooltip":"You must be signed in to make or propose changes"},"editInfo":{"editTooltip":"You must be signed in to make or propose changes"},"ghDesktopPath":"https://desktop.github.com","gitLfsPath":null,"onBranch":true,"shortPath":"16ad6a3","siteNavLoginPath":"/login?return_to=https%3A%2F%2Fgithub.com%2FADeadTrousers%2FLineageOTAstatic%2Fblob%2Fmaster%2FREADME.md","isCSV":false,"isRichtext":true,"toc":[{"level":1,"text":"Static Lineage OTA updater","anchor":"static-lineage-ota-updater","htmlText":"Static Lineage OTA updater"},{"level":2,"text":"Introduction","anchor":"introduction","htmlText":"Introduction"},{"level":2,"text":"How to use it (simple)","anchor":"how-to-use-it-simple","htmlText":"How to use it (simple)"},{"level":2,"text":"Requirements","anchor":"requirements","htmlText":"Requirements"},{"level":3,"text":"Local setup","anchor":"local-setup","htmlText":"Local setup"},{"level":3,"text":"Device setup","anchor":"device-setup","htmlText":"Device setup"},{"level":3,"text":"Release setup","anchor":"release-setup","htmlText":"Release setup"},{"level":2,"text":"Technical informations","anchor":"technical-informations","htmlText":"Technical informations"},{"level":3,"text":"Structure of the generated json file","anchor":"structure-of-the-generated-json-file","htmlText":"Structure of the generated json file"},{"level":3,"text":"Possible placeholders","anchor":"possible-placeholders","htmlText":"Possible placeholders"},{"level":3,"text":"Github api calls and rate limitation","anchor":"github-api-calls-and-rate-limitation","htmlText":"Github api calls and rate limitation"},{"level":2,"text":"Extension for other file hosters","anchor":"extension-for-other-file-hosters","htmlText":"Extension for other file hosters"},{"level":2,"text":"Not supported features","anchor":"not-supported-features","htmlText":"Not supported features"}],"lineInfo":{"truncatedLoc":"89","truncatedSloc":"75"},"mode":"file"},"image":false,"isCodeownersFile":null,"isPlain":false,"isValidLegacyIssueTemplate":false,"issueTemplateHelpUrl":"https://docs.github.com/articles/about-issue-and-pull-request-templates","issueTemplate":null,"discussionTemplate":null,"language":"Markdown","languageID":222,"large":false,"loggedIn":false,"newDiscussionPath":"/ADeadTrousers/LineageOTAstatic/discussions/new","newIssuePath":"/ADeadTrousers/LineageOTAstatic/issues/new","planSupportInfo":{"repoIsFork":null,"repoOwnedByCurrentUser":null,"requestFullPath":"/ADeadTrousers/LineageOTAstatic/blob/master/README.md","showFreeOrgGatedFeatureMessage":null,"showPlanSupportBanner":null,"upgradeDataAttributes":null,"upgradePath":null},"publishBannersInfo":{"dismissActionNoticePath":"/settings/dismiss-notice/publish_action_from_dockerfile","dismissStackNoticePath":"/settings/dismiss-notice/publish_stack_from_file","releasePath":"/ADeadTrousers/LineageOTAstatic/releases/new?marketplace=true","showPublishActionBanner":false,"showPublishStackBanner":false},"rawBlobUrl":"https://github.com/ADeadTrousers/LineageOTAstatic/raw/master/README.md","renderImageOrRaw":false,"richText":"<article class=\"markdown-body entry-content container-lg\" itemprop=\"text\"><h1 tabindex=\"-1\" id=\"user-content-static-lineage-ota-updater\" dir=\"auto\"><a class=\"heading-link\" href=\"#static-lineage-ota-updater\">Static Lineage OTA updater<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h1>\n<p dir=\"auto\">A simple way of generating the necessary json content to serve it to the Lineage OS updater using a simple file based HTTPS server.</p>\n<h2 tabindex=\"-1\" id=\"user-content-introduction\" dir=\"auto\"><a class=\"heading-link\" href=\"#introduction\">Introduction<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h2>\n<p dir=\"auto\">The main requirement for an official Lineage OS release for any device is a kernel in source code format. So this means that many devices won't get a Lineage OS release simply because there is no source code provided by the manufacturer either because they are lazy or they aren't allowed to as it is the case with Mediatek. So for any hobby developer the only possible way to provide the Lineage experience on any such devices is by offering an <em>unofficial</em> release. This also means no official OTA updates. Thankfully the Lineage OS team provided a solution:</p>\n<p dir=\"auto\">The Lineage OS updater is nothing more than a simple file download service. It uses the information provided in json format to download the required files. There are some implementations out there in the wild which use a <a href=\"https://github.com/ADeadTrousers/LineageOTA\">dynamic approach</a> but that means one needs to <em>own</em> and <em>pay</em> for webspace to just serve a simple json file.</p>\n<p dir=\"auto\">So here comes my static approach. Simply put I just use everything Github offers for free (project releases and static webpages) to provide everything needed for the Lineage OTA updater to work.</p>\n<h2 tabindex=\"-1\" id=\"user-content-how-to-use-it-simple\" dir=\"auto\"><a class=\"heading-link\" href=\"#how-to-use-it-simple\">How to use it (simple)<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h2>\n<p dir=\"auto\">If you want to use this for your own device do the following:</p>\n<ol dir=\"auto\">\n<li>Fork this repo.</li>\n<li>Make the new repo <a href=\"https://pages.github.com/\">available on <code>github.io</code></a></li>\n<li>Clone it onto your local PC.</li>\n<li>Modify <code>github.json</code> to point to your devices repo.</li>\n<li>Set the property <code>lineage.updater</code> in your <code>build.prop</code> to your new repo.</li>\n<li>Run <code>update.sh</code> (Linux) or <code>update.cmd</code> (Windows) and commit the changes back onto the repo.</li>\n<li>Repeat step 6 whenever you have created a new release.</li>\n</ol>\n<h2 tabindex=\"-1\" id=\"user-content-requirements\" dir=\"auto\"><a class=\"heading-link\" href=\"#requirements\">Requirements<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h2>\n<h3 tabindex=\"-1\" id=\"user-content-local-setup\" dir=\"auto\"><a class=\"heading-link\" href=\"#local-setup\">Local setup<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h3>\n<p dir=\"auto\">As you are quite obviously already building Lineage OS on your local machine I won't go into the details of how to setup git or python for that matter. You just need to add three more modules to python and then you are good to go. Just run the following commands either from your command prompt (Windows) or your terminal (Linux):</p>\n<div class=\"highlight highlight-source-shell notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"pip install pyparsing\npip install packaging\npip install pathvalidate\npip install tqdm\"><pre>pip install pyparsing\npip install packaging\npip install pathvalidate\npip install tqdm</pre></div>\n<h3 tabindex=\"-1\" id=\"user-content-device-setup\" dir=\"auto\"><a class=\"heading-link\" href=\"#device-setup\">Device setup<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h3>\n<p dir=\"auto\">In order to integrate this in your LineageOS based ROM, you need to add the <a href=\"https://github.com/LineageOS/android_packages_apps_Updater/blob/lineage-15.0/src/org/lineageos/updater/misc/Constants.java#L39\"><code>lineage.updater.uri</code></a> property in your <code>build.prop</code> file:</p>\n<div class=\"highlight highlight-source-ini notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"# ...\nlineage.updater.uri=https://username.github.io/LineageOTAstatic/api/v1/{device}_{type}\n# ...\"><pre><span class=\"pl-c\"><span class=\"pl-c\">#</span> ...</span>\n<span class=\"pl-k\">lineage.updater.uri</span>=https://username.github.io/LineageOTAstatic/api/v1/{device}_{type}\n<span class=\"pl-c\"><span class=\"pl-c\">#</span> ...</span></pre></div>\n<h3 tabindex=\"-1\" id=\"user-content-release-setup\" dir=\"auto\"><a class=\"heading-link\" href=\"#release-setup\">Release setup<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h3>\n<p dir=\"auto\">For your devices Github release you need to publish the following files:</p>\n<ul dir=\"auto\">\n<li><code>lineage-{version}-{timestamp}-UNOFFICIAL-{model}.zip</code></li>\n<li><code>build.prop</code> taken from <code>system</code> folder of your <code>out/target/product</code>.</li>\n<li><code>build.md5sum</code> containing at least one line with the md5 of the zip file. Best to use a similar command like:</li>\n</ul>\n<div class=\"highlight highlight-source-shell notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"md5sum lineage-{version}-{timestamp}-UNOFFICIAL-{model}.zip &gt; build.md5sum\"><pre>md5sum lineage-{version}-{timestamp}-UNOFFICIAL-{model}.zip <span class=\"pl-k\">&gt;</span> build.md5sum</pre></div>\n<h2 tabindex=\"-1\" id=\"user-content-technical-informations\" dir=\"auto\"><a class=\"heading-link\" href=\"#technical-informations\">Technical informations<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h2>\n<h3 tabindex=\"-1\" id=\"user-content-structure-of-the-generated-json-file\" dir=\"auto\"><a class=\"heading-link\" href=\"#structure-of-the-generated-json-file\">Structure of the generated json file<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h3>\n<div class=\"highlight highlight-source-json notranslate position-relative overflow-auto\" dir=\"auto\" data-snippet-clipboard-copy-content=\"{\n    &quot;response&quot;: [\n        {\n            &quot;incremental&quot;: &quot;Identification of the build; ro.build.version.incremental&quot;,\n            &quot;api_level&quot;: &quot;The api of underlying andorid; ro.build.version.sdk&quot;,\n            &quot;url&quot;: &quot;Url that points to the release zip file&quot;,\n            &quot;timestamp&quot;: Timesatmp_of_the_release,\n            &quot;md5sum&quot;: &quot;The md5 hash of the release zip file&quot;,\n            &quot;changes&quot;: &quot;Url that points to the changelog of the rleases&quot;,\n            &quot;channel&quot;: &quot;The channel this release is built upon; ro.lineage.releasetype&quot;,\n            &quot;filename&quot;: &quot;Filename of to zip file&quot;,\n            &quot;romtype&quot;: &quot;The channel this release is built upon; ro.lineage.releasetype&quot;,\n            &quot;datetime&quot;: Timesatmp_of_the_release,\n            &quot;version&quot;: &quot;The version of the lineage release; ro.lineage.build.version&quot;,\n            &quot;id&quot;: &quot;An unique identifier for this release&quot;,\n            &quot;size&quot;: The_size_of_the_zip_file\n        }\n    ]\n}\"><pre>{\n    <span class=\"pl-ent\">\"response\"</span>: [\n        {\n            <span class=\"pl-ent\">\"incremental\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>Identification of the build; ro.build.version.incremental<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"api_level\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>The api of underlying andorid; ro.build.version.sdk<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"url\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>Url that points to the release zip file<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"timestamp\"</span>: <span class=\"pl-ii\">Timesatmp_of_the_release,</span>\n            <span class=\"pl-ent\">\"md5sum\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>The md5 hash of the release zip file<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"changes\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>Url that points to the changelog of the rleases<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"channel\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>The channel this release is built upon; ro.lineage.releasetype<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"filename\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>Filename of to zip file<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"romtype\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>The channel this release is built upon; ro.lineage.releasetype<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"datetime\"</span>: <span class=\"pl-ii\">Timesatmp_of_the_release,</span>\n            <span class=\"pl-ent\">\"version\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>The version of the lineage release; ro.lineage.build.version<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"id\"</span>: <span class=\"pl-s\"><span class=\"pl-pds\">\"</span>An unique identifier for this release<span class=\"pl-pds\">\"</span></span>,\n            <span class=\"pl-ent\">\"size\"</span>: <span class=\"pl-ii\">The_size_of_the_zip_file</span>\n        }\n    ]\n}</pre></div>\n<h3 tabindex=\"-1\" id=\"user-content-possible-placeholders\" dir=\"auto\"><a class=\"heading-link\" href=\"#possible-placeholders\">Possible placeholders<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h3>\n<p dir=\"auto\">As of <a href=\"https://github.com/LineageOS/android_packages_apps_Updater/commit/5252d606716c3f8d81617babc1293c122359a94d\">5252d60</a> these placeholders are replaced at runtime:</p>\n<blockquote>\n<p dir=\"auto\">{device} - Device name</p>\n<p dir=\"auto\">{type} - Build type</p>\n<p dir=\"auto\">{incr} - Incremental version</p>\n</blockquote>\n<h3 tabindex=\"-1\" id=\"user-content-github-api-calls-and-rate-limitation\" dir=\"auto\"><a class=\"heading-link\" href=\"#github-api-calls-and-rate-limitation\">Github api calls and rate limitation<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h3>\n<p dir=\"auto\">As <a href=\"https://docs.github.com/en/developers/apps/building-github-apps/rate-limits-for-github-apps\">Github limited the rate for their api calls</a> I included a simple buffering algorithm to ensure that during testing one would not exceed the limit. When there are buffered files available you will be asked if you want to update them. So if you want to update for your latest release simply pick [Y]es as your answer.</p>\n<h2 tabindex=\"-1\" id=\"user-content-extension-for-other-file-hosters\" dir=\"auto\"><a class=\"heading-link\" href=\"#extension-for-other-file-hosters\">Extension for other file hosters<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h2>\n<p dir=\"auto\">As of now this is a very basic script which only offers Github as the file hosting service. I know there are many others out there in the wild but I neither have the time nor the will to support each and everyone. So if you want it for your own file hoster you need to adapt the script yourself. It's not that complicated and if you think your changes will make a good addition to this project simply create a pull request and I'll look into it.</p>\n<h2 tabindex=\"-1\" id=\"user-content-not-supported-features\" dir=\"auto\"><a class=\"heading-link\" href=\"#not-supported-features\">Not supported features<svg class=\"octicon octicon-link\" viewBox=\"0 0 16 16\" version=\"1.1\" width=\"16\" height=\"16\" aria-hidden=\"true\"><path d=\"m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z\"></path></svg></a></h2>\n<ul dir=\"auto\">\n<li>Incremental updates are basically impossible with this approach as you need to provide a file for every possible combination of all your releases. (At least that's how I would try to accomplish this)</li>\n</ul>\n</article>","renderedFileInfo":null,"shortPath":null,"tabSize":8,"topBannersInfo":{"overridingGlobalFundingFile":false,"globalPreferredFundingPath":null,"repoOwner":"ADeadTrousers","repoName":"LineageOTAstatic","showInvalidCitationWarning":false,"citationHelpUrl":"https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-on-github/about-citation-files","showDependabotConfigurationBanner":false,"actionsOnboardingTip":null},"truncated":false,"viewable":true,"workflowRedirectUrl":null,"symbols":{"timedOut":false,"notAnalyzed":false,"symbols":[{"name":" Static Lineage OTA updater","kind":"section_1","identStart":1,"identEnd":28,"extentStart":0,"extentEnd":5562,"fullyQualifiedName":" Static Lineage OTA updater","identUtf16":{"start":{"lineNumber":0,"utf16Col":1},"end":{"lineNumber":0,"utf16Col":28}},"extentUtf16":{"start":{"lineNumber":0,"utf16Col":0},"end":{"lineNumber":89,"utf16Col":0}}},{"name":" Introduction","kind":"section_2","identStart":164,"identEnd":177,"extentStart":162,"extentEnd":1313,"fullyQualifiedName":" Introduction","identUtf16":{"start":{"lineNumber":3,"utf16Col":2},"end":{"lineNumber":3,"utf16Col":15}},"extentUtf16":{"start":{"lineNumber":3,"utf16Col":0},"end":{"lineNumber":10,"utf16Col":0}}},{"name":" How to use it (simple)","kind":"section_2","identStart":1315,"identEnd":1338,"extentStart":1313,"extentEnd":1814,"fullyQualifiedName":" How to use it (simple)","identUtf16":{"start":{"lineNumber":10,"utf16Col":2},"end":{"lineNumber":10,"utf16Col":25}},"extentUtf16":{"start":{"lineNumber":10,"utf16Col":0},"end":{"lineNumber":20,"utf16Col":0}}},{"name":" Requirements","kind":"section_2","identStart":1816,"identEnd":1829,"extentStart":1814,"extentEnd":3096,"fullyQualifiedName":" Requirements","identUtf16":{"start":{"lineNumber":20,"utf16Col":2},"end":{"lineNumber":20,"utf16Col":15}},"extentUtf16":{"start":{"lineNumber":20,"utf16Col":0},"end":{"lineNumber":48,"utf16Col":0}}},{"name":" Local setup","kind":"section_3","identStart":1834,"identEnd":1846,"extentStart":1831,"extentEnd":2277,"fullyQualifiedName":" Local setup","identUtf16":{"start":{"lineNumber":22,"utf16Col":3},"end":{"lineNumber":22,"utf16Col":15}},"extentUtf16":{"start":{"lineNumber":22,"utf16Col":0},"end":{"lineNumber":31,"utf16Col":0}}},{"name":" Device setup","kind":"section_3","identStart":2280,"identEnd":2293,"extentStart":2277,"extentEnd":2676,"fullyQualifiedName":" Device setup","identUtf16":{"start":{"lineNumber":31,"utf16Col":3},"end":{"lineNumber":31,"utf16Col":16}},"extentUtf16":{"start":{"lineNumber":31,"utf16Col":0},"end":{"lineNumber":39,"utf16Col":0}}},{"name":" Release setup","kind":"section_3","identStart":2679,"identEnd":2693,"extentStart":2676,"extentEnd":3096,"fullyQualifiedName":" Release setup","identUtf16":{"start":{"lineNumber":39,"utf16Col":3},"end":{"lineNumber":39,"utf16Col":17}},"extentUtf16":{"start":{"lineNumber":39,"utf16Col":0},"end":{"lineNumber":48,"utf16Col":0}}},{"name":" Technical informations","kind":"section_2","identStart":3098,"identEnd":3121,"extentStart":3096,"extentEnd":4851,"fullyQualifiedName":" Technical informations","identUtf16":{"start":{"lineNumber":48,"utf16Col":2},"end":{"lineNumber":48,"utf16Col":25}},"extentUtf16":{"start":{"lineNumber":48,"utf16Col":0},"end":{"lineNumber":84,"utf16Col":0}}},{"name":" Structure of the generated json file","kind":"section_3","identStart":3126,"identEnd":3163,"extentStart":3123,"extentEnd":4112,"fullyQualifiedName":" Structure of the generated json file","identUtf16":{"start":{"lineNumber":50,"utf16Col":3},"end":{"lineNumber":50,"utf16Col":40}},"extentUtf16":{"start":{"lineNumber":50,"utf16Col":0},"end":{"lineNumber":73,"utf16Col":0}}},{"name":" Possible placeholders","kind":"section_3","identStart":4115,"identEnd":4137,"extentStart":4112,"extentEnd":4396,"fullyQualifiedName":" Possible placeholders","identUtf16":{"start":{"lineNumber":73,"utf16Col":3},"end":{"lineNumber":73,"utf16Col":25}},"extentUtf16":{"start":{"lineNumber":73,"utf16Col":0},"end":{"lineNumber":81,"utf16Col":0}}},{"name":" Github api calls and rate limitation","kind":"section_3","identStart":4399,"identEnd":4436,"extentStart":4396,"extentEnd":4851,"fullyQualifiedName":" Github api calls and rate limitation","identUtf16":{"start":{"lineNumber":81,"utf16Col":3},"end":{"lineNumber":81,"utf16Col":40}},"extentUtf16":{"start":{"lineNumber":81,"utf16Col":0},"end":{"lineNumber":84,"utf16Col":0}}},{"name":" Extension for other file hosters","kind":"section_2","identStart":4853,"identEnd":4886,"extentStart":4851,"extentEnd":5334,"fullyQualifiedName":" Extension for other file hosters","identUtf16":{"start":{"lineNumber":84,"utf16Col":2},"end":{"lineNumber":84,"utf16Col":35}},"extentUtf16":{"start":{"lineNumber":84,"utf16Col":0},"end":{"lineNumber":87,"utf16Col":0}}},{"name":" Not supported features","kind":"section_2","identStart":5336,"identEnd":5359,"extentStart":5334,"extentEnd":5562,"fullyQualifiedName":" Not supported features","identUtf16":{"start":{"lineNumber":87,"utf16Col":2},"end":{"lineNumber":87,"utf16Col":25}},"extentUtf16":{"start":{"lineNumber":87,"utf16Col":0},"end":{"lineNumber":89,"utf16Col":0}}}]}},"copilotInfo":null,"copilotAccessAllowed":false,"csrf_tokens":{"/ADeadTrousers/LineageOTAstatic/branches":{"post":"gh9_tjSv7LNJea9N8bPLl7QXzUlDYNHCPNheOn-Q5kjQBrMZCqmxUhdmYtcRMQrVzha3ZLCmG7RIehinNc5IIA"},"/repos/preferences":{"post":"mUNHT-yTeEziV7UIjZs2xGNPnBNk5wOscBTqhh4W24TVI_bb5av3kxkXFveSqL0BGxLlTLj2bte9HOSWG_IMiw"}}},"title":"LineageOTAstatic/README.md at master · ADeadTrousers/LineageOTAstatic"}