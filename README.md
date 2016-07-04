<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html expr:dir='data:blog.languageDirection' lang='zh-TW' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
<head>
    <meta content='500674948' property='fb:admins'/>
    <b:include data='blog' name='all-head-content'/>
    <title><data:blog.pageTitle/></title>
    <link href='http://coscup.org/2011-theme/assets/mobile.css' media='handheld, screen and (max-width: 480px)' rel='stylesheet' type='text/css'/>
    <link href='http://coscup.org/2011-theme/assets/style.css' media='print, screen and (min-width: 481px)' rel='stylesheet' type='text/css'/>
    <!--[if lte IE 8]><link rel="stylesheet" type="text/css" href="http://coscup.org/2011-theme/assets/style.css" media="print, screen"/><![endif]-->
    <link href='http://coscup.org/2011-theme/assets/favicon.ico' rel='shortcut icon' type='image/x-icon'/>
    <meta content='width=device-width' name='viewport'/>
    <meta content='http://coscup.org/2011-theme/assets/coscup.png' property='og:image'/>
    <meta content='yes' name='apple-mobile-web-app-capable'/>
    <meta content='black' name='apple-mobile-web-app-status-bar-style'/>
    <meta content='yes' name='apple-touch-fullscreen'/>
    <link href='http://coscup.org/2011-theme/assets/coscup-icon-iphone.png' rel='apple-touch-icon'/>
    <link href='http://coscup.org/2011-theme/assets/coscup-icon-ipad.png' rel='apple-touch-icon' sizes='72x72'/>
    <link href='http://coscup.org/2011-theme/assets/coscup-icon-iphone4.png' rel='apple-touch-icon' sizes='114x114'/>
<b:skin><![CDATA[
/* Variable definitions
   ====================
   <Variable name="startSide" description="Side where text starts in blog language"
             type="automatic" default="left" value="left">
*/
#navbar, #blog-pager .home-link, .blog-feeds {
    display: none;
}
.date-header {
	float: right;
	margin-left: 1em;
}
.post-title {
    /* border-bottom: 2px solid #333; */
}
#sidebar2 iframe {
	background-color: #fff;
}
.fb_iframe_widget {
	display: block !important;
}
.fb_iframe_widget iframe {
	width: 100% !important;
}
.post-footer {
	margin-top: 1em;
	border-top: 1px solid #ccc;
	font-size: 0.8em;
}
.date-posts {
	margin-bottom: 5em;
}
]]></b:skin>
<!-- Google Analytics js code -->
<script type='text/javascript'>
//<![CDATA[
    var _gaq = _gaq || [];
        _gaq.push(['_setAccount', 'UA-12923351-2']);
        _gaq.push(['_trackPageview']);
    (function() {
        var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
        ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
        var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
    })();
//]]>
</script>
</head>
<body>
<div id='header'>
    <div class='info'>
        <h1><a href='http://coscup.org/2011/zh-tw/' title='首頁'>COSCUP</a></h1>
        <p id='title'>開源人年會</p>
        <p id='title_en'>Conference for Open Source <span id='coders'>Coders</span>, <span id='users'>Users</span> and <span id='promoters'>Promoters</span></p>
        <p id='date_place' title='2011 年 8 月 20 – 21 日'><span id='date'>8/20 &#8211; 21, 2011</span><span id='place'>台灣台北</span></p>
        <div class='empty' id='nav'>
        <!-- 上面的 class="empty" 會觸發 script 拉遠端資料顯示 -->
        </div>
        <div id='language'>
            <ul>
                <li><a href='http://coscup.org/2011/en/' lang='en' title='English'>English</a></li>
                <li><a href='http://coscup.org/2011/zh-tw/' lang='zh-TW' title='正體中文'>正體中文</a></li>
                <li><a href='http://coscup.org/2011/zh-cn/' lang='zh-CN' title='简体中文'>简体中文</a></li>
            </ul>
        </div>
        <div id='message'>
            <p>Come on rock with <em>Gadgets beyond Smartphones</em>!</p>
        </div>
        <p id='mascot_icon'/>
        <div id='connect_box'>
            <ul>
                <li><a href='https://www.google.com/calendar/event?action=TEMPLATE&amp;text=COSCUP+2011&amp;dates=20110820T010000Z/20110821T100000Z&amp;details=http%3A%2F%2Fcoscup.org/2011/&amp;trp=true&amp;sprop=http%3A%2F%2Fcoscup.org/2011/&amp;sprop=name:COSCUP' target='_blank' title='加到 Google 日曆'><span class='sprite gcal'/></a></li>
				<li><a href='http://coscup.org/2011/zh-tw/contact/#subscribe' target='_blank' title='訂閱電子報'><span class='sprite newspaper'/></a></li>
                <li><a href='https://www.facebook.com/coscup' target='_blank' title='Facebook 粉絲團'><span class='sprite facebook'/></a></li>
                <li><a href='https://twitter.com/coscup' target='_blank' title='Twitter'><span class='sprite twitter'/></a></li>
                <li><a href='http://www.plurk.com/coscup' target='_blank' title='噗浪'><span class='sprite plurk'/></a></li>
                <li><a href='http://feeds.feedburner.com/coscup' target='_blank' title='部落格 RSS Feed'><span class='sprite rss'/></a></li>
            </ul>
        </div>
    </div>
</div>
<div id='content'>
<!-- content // -->
	<b:if cond='data:blog.url == data:blog.homepageUrl'>
		<b:section class='hideInMobile' id='sidebar2' preferred='yes'>
<b:widget id='HTML3' locked='false' title='' type='HTML' version='1' visible='true'>
  <b:includable id='main'>
					<div class='widget-content'>
						<data:content/>
					</div>
					<b:include name='quickedit'/>
				</b:includable>
</b:widget>
<b:widget id='BlogArchive1' locked='false' title='網誌存檔' type='BlogArchive' version='1' visible='true'>
  <b:includable id='main'>
					<b:if cond='data:title'>
						<h2><data:title/></h2>
					</b:if>
					<div class='widget-content'>
						<div id='ArchiveList'>
							<div expr:id='data:widget.instanceId + &quot;_ArchiveList&quot;'>
								<b:if cond='data:style == &quot;HIERARCHY&quot;'>
									<b:include data='data' name='interval'/>
								</b:if>
								<b:if cond='data:style == &quot;FLAT&quot;'>
									<b:include data='data' name='flat'/>
								</b:if>
								<b:if cond='data:style == &quot;MENU&quot;'>
									<b:include data='data' name='menu'/>
								</b:if>
							</div>
						</div>
						<b:include name='quickedit'/>
					</div>
				</b:includable>
  <b:includable id='flat' var='data'>
					<ul class='flat'>
						<b:loop values='data:data' var='i'>
							<li class='archivedate'>
								<a expr:href='data:i.url'><data:i.name/></a> (<data:i.post-count/>)
							</li>
						</b:loop>
					</ul>
				</b:includable>
  <b:includable id='interval' var='intervalData'>
					<b:loop values='data:intervalData' var='i'>
						<ul class='hierarchy'>
							<li expr:class='&quot;archivedate &quot; + data:i.expclass'>
								<b:include data='i' name='toggle'/>
								<a class='post-count-link' expr:href='data:i.url'><data:i.name/></a>
								<span class='post-count' dir='ltr'>(<data:i.post-count/>)</span>
								<b:if cond='data:i.data'>
									<b:include data='i.data' name='interval'/>
								</b:if>
								<b:if cond='data:i.posts'>
									<b:include data='i.posts' name='posts'/>
								</b:if>
							</li>
						</ul>
					</b:loop>
				</b:includable>
  <b:includable id='menu' var='data'>
					<select expr:id='data:widget.instanceId + &quot;_ArchiveMenu&quot;'>
						<option value=''><data:title/></option>
						<b:loop values='data:data' var='i'>
							<option expr:value='data:i.url'><data:i.name/> (<data:i.post-count/>)</option>
						</b:loop>
					</select>
				</b:includable>
  <b:includable id='posts' var='posts'>
					<ul class='posts'>
						<b:loop values='data:posts' var='i'>
							<li><a expr:href='data:i.url'><data:i.title/></a></li>
						</b:loop>
					</ul>
				</b:includable>
  <b:includable id='toggle' var='interval'>
					<b:if cond='data:interval.toggleId'>
						<b:if cond='data:interval.expclass == &quot;expanded&quot;'>
							<a class='toggle' href='javascript:void(0)'>
								<span class='zippy toggle-open'>&#9660;&#160;</span>
							</a>
							<b:else/>
							<a class='toggle' href='javascript:void(0)'>
								<span class='zippy'>
									<b:if cond='data:blog.languageDirection == &quot;rtl&quot;'>
										&#9668;&#160;
										<b:else/>
										&#9658;&#160;
									</b:if>
								</span>
							</a>
						</b:if>
					</b:if>
				</b:includable>
</b:widget>
</b:section>
	</b:if>
	<!-- blogger data -->
	<b:section id='main-blogger' showaddelement='no'>
<b:widget id='Blog1' locked='true' title='Posting Blog' type='Blog' version='1' visible='true'>
  <b:includable id='main' var='top'>
				<b:if cond='data:top.showDummy'>
					<script expr:src='data:top.dummyUrl'>{&#39;lang&#39;: &#39;<data:top.languageCode/>&#39;}</script>
				</b:if>
				<b:if cond='data:mobileindex'>
					<!-- mobile index -->
					<div class='blog-posts hfeed'>
						<b:loop values='data:posts' var='post'>
							<b:if cond='data:post.isFirstPost == &quot;false&quot;'>
								&lt;/div&gt;
							</b:if>
							&lt;div class=&quot;mobile-date-outer date-outer&quot;&gt;
							<b:include data='post' name='mobile-index-post'/>
							<b:if cond='data:post.trackLatency'>
								<data:post.latencyJs/>
							</b:if>
						</b:loop>
						<b:if cond='data:numPosts != 0'>
							&lt;/div&gt;
						</b:if>
					</div>
					<b:else/>
					<!-- posts -->
					<div class='blog-posts hfeed'>
						<b:include data='top' name='status-message'/>
						<data:defaultAdStart/>
						<b:loop values='data:posts' var='post'>
							<b:if cond='data:post.isDateStart'>
								<b:if cond='data:post.isFirstPost == &quot;false&quot;'>
									&lt;/div&gt;&lt;/div&gt;
								</b:if>
							</b:if>
							<b:if cond='data:post.isDateStart'>
								&lt;div class=&quot;date-outer&quot;&gt;
							</b:if>
							<b:if cond='data:post.dateHeader'>
								<span class='date-header'><data:post.dateHeader/></span>
							</b:if>
							<b:if cond='data:post.isDateStart'>
								&lt;div class=&quot;date-posts&quot;&gt;
							</b:if>
							<div class='post-outer'>
								<b:include data='post' name='post'/>
								<b:if cond='data:blog.pageType == &quot;static_page&quot;'>
									<b:include data='post' name='comments'/>
								</b:if>
								<b:if cond='data:blog.pageType == &quot;item&quot;'>
									<b:include data='post' name='comments'/>
								</b:if>
							</div>
							<b:if cond='data:post.includeAd'>
								<b:if cond='data:post.isFirstPost'>
									<data:defaultAdEnd/>
									<b:else/>
									<data:adEnd/>
								</b:if>
								<b:if cond='data:mobile == &quot;false&quot;'>
									<div class='inline-ad'>
										<data:adCode/>
									</div>
								</b:if>
								<data:adStart/>
							</b:if>
							<b:if cond='data:post.trackLatency'>
								<data:post.latencyJs/>
							</b:if>
						</b:loop>
						<b:if cond='data:numPosts != 0'>
							&lt;/div&gt;&lt;/div&gt;
						</b:if>
						<data:adEnd/>
					</div>
				</b:if>
				<!-- navigation -->
				<b:if cond='data:mobile'>
					<b:include name='mobile-nextprev'/>
					<b:else/>
					<b:include name='nextprev'/>
					<!-- feed links -->
					<b:include name='feedLinks'/>
				</b:if>
				<b:if cond='data:top.showStars'>
					<script src='//www.google.com/jsapi' type='text/javascript'/>
					<script type='text/javascript'>
		google.load(&quot;annotations&quot;, &quot;1&quot;, {&quot;locale&quot;: &quot;<data:top.languageCode/>&quot;});
		function initialize() {
			google.annotations.setApplicationId(<data:top.blogspotReviews/>);
			google.annotations.createAll();
			google.annotations.fetch();
		}
		google.setOnLoadCallback(initialize);
					</script>
				</b:if>
			</b:includable>
  <b:includable id='backlinkDeleteIcon' var='backlink'>
				<span expr:class='&quot;item-control &quot; + data:backlink.adminClass'>
					<a expr:href='data:backlink.deleteUrl' expr:title='data:top.deleteBacklinkMsg'>
						<img src='//www.blogger.com/img/icon_delete13.gif'/>
					</a>
				</span>
			</b:includable>
  <b:includable id='backlinks' var='post'>
				<a name='links'/><h4><data:post.backlinksLabel/></h4>
				<b:if cond='data:post.numBacklinks != 0'>
					<dl class='comments-block' id='comments-block'>
						<b:loop values='data:post.backlinks' var='backlink'>
							<div class='collapsed-backlink backlink-control'>
								<dt class='comment-title'>
									<span class='backlink-toggle-zippy'>&#160;</span>
									<a expr:href='data:backlink.url' rel='nofollow'><data:backlink.title/></a>
									<b:include data='backlink' name='backlinkDeleteIcon'/>
								</dt>
								<dd class='comment-body collapseable'>
									<data:backlink.snippet/>
								</dd>
								<dd class='comment-footer collapseable'>
									<span class='comment-author'><data:post.authorLabel/> <data:backlink.author/></span>
									<span class='comment-timestamp'><data:post.timestampLabel/> <data:backlink.timestamp/></span>
								</dd>
							</div>
						</b:loop>
					</dl>
				</b:if>
				<p class='comment-footer'>
					<a class='comment-link' expr:href='data:post.createLinkUrl' expr:id='data:widget.instanceId + &quot;_backlinks-create-link&quot;' target='_blank'><data:post.createLinkLabel/></a>
				</p>
			</b:includable>
  <b:includable id='comment-form' var='post'>
				<div class='comment-form'>
					<a name='comment-form'/>
					<b:if cond='data:mobile'>
						<h4 id='comment-post-message'>
							<a expr:id='data:widget.instanceId + &quot;_comment-editor-toggle-link&quot;' href='javascript:void(0)'><data:postCommentMsg/></a></h4>
						<p><data:blogCommentMessage/></p>
						<data:blogTeamBlogMessage/>
						<a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
						<iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
						<b:else/>
						<h4 id='comment-post-message'><data:postCommentMsg/></h4>
						<p><data:blogCommentMessage/></p>
						<data:blogTeamBlogMessage/>
						<a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
						<iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
					</b:if>
					<data:post.friendConnectJs/>
					<data:post.cmtfpIframe/>
					<script type='text/javascript'>
		BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
					</script>
				</div>
			</b:includable>
  <b:includable id='commentDeleteIcon' var='comment'>
				<span expr:class='&quot;item-control &quot; + data:comment.adminClass'>
					<b:if cond='data:showCmtPopup'>
						<div class='goog-toggle-button'>
							<div class='goog-inline-block comment-action-icon'/>
						</div>
						<b:else/>
						<a class='comment-delete' expr:href='data:comment.deleteUrl' expr:title='data:top.deleteCommentMsg'>
							<img src='//www.blogger.com/img/icon_delete13.gif'/>
						</a>
					</b:if>
				</span>
			</b:includable>
  <b:includable id='comment_count_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <span class='cmt_count_iframe_holder' expr:data-count='data:post.numComments' expr:data-onclick='data:post.addCommentOnclick' expr:data-post-url='data:post.url' expr:data-url='data:post.url.canonical.http'>
    </span>
  <b:else/>
    <a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'>
      <data:post.commentLabelFull/>:
    </a>
  </b:if>
</b:includable>
  <b:includable id='comment_picker' var='post'>
  <b:if cond='data:post.commentSource == 1'>
    <b:include data='post' name='iframe_comments'/>
  <b:elseif cond='data:post.showThreadedComments'/>
    <b:include data='post' name='threaded_comments'/>
  <b:else/>
    <b:include data='post' name='comments'/>
  </b:if>
</b:includable>
  <b:includable id='comments' var='post'>
				<div class='comments' id='comments'>
					<a name='comments'/>
					<iframe allowTransparency='true' expr:src='&quot;http://www.facebook.com/plugins/like.php?href=&quot; + data:post.url + &quot;&amp;layout=standard&amp;show_faces=true&amp;action=like&amp;font&amp;colorscheme=light&amp;height=80&quot;' frameborder='0' scrolling='no' style='border:none; overflow:hidden; width: 100%; height:80px;'/>
					<div id='fb-root'/><script src='http://connect.facebook.net/zh_TW/all.js#appId=APP_ID&amp;xfbml=1'/><fb:comments expr:href='data:post.url' num_posts='2' width='500'/>
					<b:if cond='data:post.allowComments'>
						<h4>
							<b:if cond='data:post.numComments == 1'>
								1 <data:commentLabel/>:
								<b:else/>
								<data:post.numComments/> <data:commentLabelPlural/>:
							</b:if>
						</h4>
						<b:if cond='data:post.commentPagingRequired'>
							<span class='paging-control-container'>
							<a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'><data:post.oldestLinkText/></a>
							&#160;
							<a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'><data:post.olderLinkText/></a>
							&#160;
							<data:post.commentRangeText/>
							&#160;
							<a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'><data:post.newerLinkText/></a>
							&#160;
							<a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'><data:post.newestLinkText/></a>
							</span>
						</b:if>	
						<div expr:id='data:widget.instanceId + &quot;_comments-block-wrapper&quot;'>
							<dl expr:class='data:post.avatarIndentClass' id='comments-block'>
								<b:loop values='data:post.comments' var='comment'>
									<dt expr:class='&quot;comment-author &quot; + data:comment.authorClass' expr:id='data:comment.anchorName'>
										<b:if cond='data:comment.favicon'>
											<img expr:src='data:comment.favicon' height='16px' style='margin-bottom:-2px;' width='16px'/>
										</b:if>
										<a expr:name='data:comment.anchorName'/>
										<b:if cond='data:blog.enabledCommentProfileImages'>
											<data:comment.authorAvatarImage/>
										</b:if>
										<b:if cond='data:comment.authorUrl'>
											<a expr:href='data:comment.authorUrl' rel='nofollow'><data:comment.author/></a>
											<b:else/>
											<data:comment.author/>
										</b:if>
										<data:commentPostedByMsg/>
									</dt>
									<dd class='comment-body' expr:id='data:widget.instanceId + data:comment.cmtBodyIdPostfix'>
										<b:if cond='data:comment.isDeleted'>
											<span class='deleted-comment'><data:comment.body/></span>
											<b:else/>
											<p>
												<data:comment.body/>
											</p>
										</b:if>
									</dd>
									<dd class='comment-footer'>
										<span class='comment-timestamp'>
											<a expr:href='data:comment.url' title='comment permalink'>
												<data:comment.timestamp/>
											</a>
											<b:include data='comment' name='commentDeleteIcon'/>
										</span>
									</dd>
								</b:loop>
							</dl>
						</div>	
						<b:if cond='data:post.commentPagingRequired'>
							<span class='paging-control-container'>
								<a expr:class='data:post.oldLinkClass' expr:href='data:post.oldestLinkUrl'>
									<data:post.oldestLinkText/>
								</a>
								<a expr:class='data:post.oldLinkClass' expr:href='data:post.olderLinkUrl'>
									<data:post.olderLinkText/>
								</a>
								&#160;
								<data:post.commentRangeText/>
								&#160;
								<a expr:class='data:post.newLinkClass' expr:href='data:post.newerLinkUrl'>
									<data:post.newerLinkText/>
								</a>
								<a expr:class='data:post.newLinkClass' expr:href='data:post.newestLinkUrl'>
									<data:post.newestLinkText/>
								</a>
							</span>
						</b:if>
						<p class='comment-footer'>
							<b:if cond='data:post.embedCommentForm'>
								<b:if cond='data:post.allowNewComments'>
									<b:include data='post' name='comment-form'/>
									<b:else/>
									<data:post.noNewCommentsText/>
								</b:if>
								<b:else/>
								<b:if cond='data:post.allowComments'>
									<a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
								</b:if>
							</b:if>
						</p>
					</b:if>
					<b:if cond='data:showCmtPopup'>
						<div id='comment-popup'>
							<iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
							</iframe>
						</div>
					</b:if>
					<div id='backlinks-container'>
						<div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
							<b:if cond='data:post.showBacklinks'>
								<b:include data='post' name='backlinks'/>
							</b:if>
						</div>
					</div>
				</div>
			</b:includable>
  <b:includable id='feedLinks'>
  <b:if cond='data:blog.pageType != &quot;item&quot;'> <!-- Blog feed links -->
    <b:if cond='data:feedLinks'>
      <div class='blog-feeds'>
        <b:include data='feedLinks' name='feedLinksBody'/>
      </div>
    </b:if>

  <b:else/> <!--Post feed links -->
    <div class='post-feeds'>
      <b:loop values='data:posts' var='post'>
        <b:include cond='data:post.allowComments and data:post.feedLinks' data='post.feedLinks' name='feedLinksBody'/>
      </b:loop>
    </div>
  </b:if>
</b:includable>
  <b:includable id='feedLinksBody' var='links'>
				<div class='feed-links'>
					<data:feedLinksMsg/>
					<b:loop values='data:links' var='f'>
						<a class='feed-link' expr:href='data:f.url' expr:type='data:f.mimeType' target='_blank'><data:f.name/> (<data:f.feedType/>)</a>
					</b:loop>
				</div>
			</b:includable>
  <b:includable id='iframe_comments' var='post'>

  <b:if cond='data:post.allowIframeComments'>
    <script expr:src='data:post.iframeCommentSrc' type='text/javascript'/>
    <div class='cmt_iframe_holder' expr:data-href='data:post.url.canonical' expr:data-viewtype='data:post.viewType'/>

    <b:if cond='data:post.embedCommentForm == &quot;false&quot;'>
      <a expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><data:postCommentMsg/></a>
    </b:if>
  </b:if>
</b:includable>
  <b:includable id='mobile-index-post' var='post'>
				<b:if cond='data:post.dateHeader'>
					<div class='mobile-index-date'>
						<div class='date-header'>
							<data:post.dateHeader/>
						</div>
					</div>
				</b:if>	
				<div class='mobile-post-outer'>
					<a expr:href='data:post.url'>
						<div class='mobile-index-title-outer'>
							<h2 class='mobile-index-title entry-title'>
								<data:post.title/>
							</h2>
						</div>
						<div>
							<div class='mobile-index-arrow'>
								&amp;rsaquo;
							</div>			
							<div class='mobile-index-contents'>
								<b:if cond='data:post.thumbnailUrl'>
									<div class='mobile-index-thumbnail'>
										<div class='Image'>
											<img expr:src='data:post.thumbnailUrl'/>
										</div>
									</div>
								</b:if>
								<div class='post-body'>
									<b:if cond='data:post.snippet'><data:post.snippet/></b:if>
								</div>
							</div>
							<div style='clear: both;'/>
						</div>
					</a>
					<div class='mobile-index-comment'>
						<b:if cond='data:blog.pageType != &quot;item&quot;'>
							<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
								<b:if cond='data:post.allowComments'>
									<b:if cond='data:post.numComments != 0'>
										<a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
									</b:if>
								</b:if>
							</b:if>
						</b:if>
					</div>
				</div>
			</b:includable>
  <b:includable id='mobile-main' var='top'>
    <!-- posts -->
    <div class='blog-posts hfeed'>

      <b:include data='top' name='status-message'/>

      <b:if cond='data:blog.pageType == &quot;index&quot;'>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-index-post'/>
        </b:loop>
      <b:else/>
        <b:loop values='data:posts' var='post'>
          <b:include data='post' name='mobile-post'/>
        </b:loop>
      </b:if>
    </div>

   <b:include name='mobile-nextprev'/>
</b:includable>
  <b:includable id='mobile-nextprev'>
				<div class='blog-pager' id='blog-pager'>
					<b:if cond='data:newerPageUrl'>
						<div class='mobile-link-button' id='blog-pager-newer-link'>
							<a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'>&amp;laquo;</a>
						</div>
					</b:if>
					<b:if cond='data:olderPageUrl'>
						<div class='mobile-link-button' id='blog-pager-older-link'>
							<a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'>&amp;raquo;</a>
						</div>
					</b:if>
					<div class='mobile-link-button' id='blog-pager-home-link'>
						<a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>
					</div>
					<div class='mobile-desktop-link'>
						<a class='home-link' expr:href='data:desktopLinkUrl'><data:desktopLinkMsg/></a>
					</div>
				</div>
				<div class='clear'/>
			</b:includable>
  <b:includable id='mobile-post' var='post'>
  <div class='date-outer'>
    <b:if cond='data:post.dateHeader'>
      <h2 class='date-header'><span><data:post.dateHeader/></span></h2>
    </b:if>
    <div class='date-posts'>
      <div class='post-outer'>

        <div class='post hentry uncustomized-post-template' itemscope='itemscope' itemtype='http://schema.org/BlogPosting'>
          <b:if cond='data:post.thumbnailUrl'>
            <meta expr:content='data:post.thumbnailUrl' itemprop='image_url'/>
          </b:if>
          <meta expr:content='data:blog.blogId' itemprop='blogId'/>
          <meta expr:content='data:post.id' itemprop='postId'/>

          <a expr:name='data:post.id'/>
          <b:if cond='data:post.title'>
            <h3 class='post-title entry-title' itemprop='name'>
              <b:if cond='data:post.link'>
                <a expr:href='data:post.link'><data:post.title/></a>
              <b:elseif cond='data:post.url and data:blog.url != data:post.url'/>
                <a expr:href='data:post.url'><data:post.title/></a>
              <b:else/>
                <data:post.title/>
              </b:if>
            </h3>
          </b:if>

          <div class='post-header'>
            <div class='post-header-line-1'/>
          </div>

          <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id' itemprop='articleBody'>
            <data:post.body/>
            <div style='clear: both;'/> <!-- clear for photos floats -->
          </div>

          <div class='post-footer'>
            <div class='post-footer-line post-footer-line-1'>
              <span class='post-author vcard'>
                <b:if cond='data:top.showAuthor'>
                  <b:if cond='data:post.authorProfileUrl'>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <meta expr:content='data:post.authorProfileUrl' itemprop='url'/>
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'>
                        <span itemprop='name'><data:post.author/></span>
                      </a>
                    </span>
                  <b:else/>
                    <span class='fn' itemprop='author' itemscope='itemscope' itemtype='http://schema.org/Person'>
                      <span itemprop='name'><data:post.author/></span>
                    </span>
                  </b:if>
                </b:if>
              </span>

              <span class='post-timestamp'>
                <b:if cond='data:top.showTimestamp'>
                  <data:top.timestampLabel/>
                  <b:if cond='data:post.url'>
                    <meta expr:content='data:post.url.canonical' itemprop='url'/>
                    <a class='timestamp-link' expr:href='data:post.url' rel='bookmark' title='permanent link'><abbr class='published' expr:title='data:post.timestampISO8601' itemprop='datePublished'><data:post.timestamp/></abbr></a>
                  </b:if>
                </b:if>
              </span>

              <span class='post-comment-link'>
                <b:include cond='data:blog.pageType not in {&quot;item&quot;,&quot;static_page&quot;}                                  and data:post.allowComments' data='post' name='comment_count_picker'/>
              </span>
            </div>

            <div class='post-footer-line post-footer-line-2'>
              <b:if cond='data:top.showMobileShare'>
                <div class='mobile-link-button goog-inline-block' id='mobile-share-button'>
                  <a href='javascript:void(0);'><data:shareMsg/></a>
                </div>
              </b:if>
              <b:if cond='data:top.showDummy'>
                <div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
              </b:if>
            </div>

          </div>
        </div>

        <b:include cond='data:blog.pageType in {&quot;static_page&quot;,&quot;item&quot;}' data='post' name='comment_picker'/>
      </div>
    </div>
  </div>
</b:includable>
  <b:includable id='nextprev'>
  <div class='blog-pager' id='blog-pager'>
    <b:if cond='data:newerPageUrl'>
      <span id='blog-pager-newer-link'>
      <a class='blog-pager-newer-link' expr:href='data:newerPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-newer-link&quot;' expr:title='data:newerPageTitle'><data:newerPageTitle/></a>
      </span>
    </b:if>

    <b:if cond='data:olderPageUrl'>
      <span id='blog-pager-older-link'>
      <a class='blog-pager-older-link' expr:href='data:olderPageUrl' expr:id='data:widget.instanceId + &quot;_blog-pager-older-link&quot;' expr:title='data:olderPageTitle'><data:olderPageTitle/></a>
      </span>
    </b:if>

    <a class='home-link' expr:href='data:blog.homepageUrl'><data:homeMsg/></a>

    <b:if cond='data:mobileLinkUrl'>
      <div class='blog-mobile-link'>
        <a expr:href='data:mobileLinkUrl'><data:mobileLinkMsg/></a>
      </div>
    </b:if>

  </div>
  <div class='clear'/>
</b:includable>
  <b:includable id='post' var='post'>
				<div class='post hentry'>
					<a expr:name='data:post.id'/>
					<b:if cond='data:post.title'>
						<h2 class='post-title entry-title'>
							<b:if cond='data:post.link'>
								<a expr:href='data:post.link'><data:post.title/></a>
								<b:else/>
								<b:if cond='data:post.url'>
									<b:if cond='data:blog.url != data:post.url'>
										<a expr:href='data:post.url'><data:post.title/></a>
										<b:else/>
										<data:post.title/>
									</b:if>
									<b:else/>
									<data:post.title/>
								</b:if>
							</b:if>
						</h2>
					</b:if>	
					<div class='post-header'>
						<div class='post-header-line-1'/>
					</div>
					<div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
						<data:post.body/>
						<div style='clear: both;'/> <!-- clear for photos floats -->
					</div>
					<b:if cond='data:post.hasJumpLink'>
						<div class='jump-link'>
							<a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
						</div>
					</b:if>
					<div class='post-footer'>
						<div class='post-footer-line post-footer-line-1'><span class='post-comment-link'>
								<b:if cond='data:blog.pageType != &quot;item&quot;'>
									<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
										<b:if cond='data:post.allowComments'>
											<a class='comment-link' expr:href='data:post.addCommentUrl' expr:onclick='data:post.addCommentOnclick'><b:if cond='data:post.numComments == 1'>1 <data:top.commentLabel/><b:else/><data:post.numComments/> <data:top.commentLabelPlural/></b:if></a>
										</b:if>
									</b:if>
								</b:if>
							</span> <span class='post-labels'>
								<b:if cond='data:post.labels'>
									<data:postLabelsLabel/>
									<b:loop values='data:post.labels' var='label'>
										<a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
									</b:loop>
								</b:if>
							</span> <span class='post-icons'>
								<!-- email post links -->
								<b:if cond='data:post.emailPostUrl'>
									<span class='item-action'>
										<a expr:href='data:post.emailPostUrl' expr:title='data:top.emailPostMsg'>
											<img alt='' class='icon-action' height='13' src='http://img1.blogblog.com/img/icon18_email.gif' width='18'/>
										</a>
									</span>
								</b:if>
								<!-- quickedit pencil -->
								<b:include data='post' name='postQuickEdit'/>
								</span> </div>
					
					<div class='post-footer-line post-footer-line-2'/>
					<div class='post-footer-line post-footer-line-3'/>
					</div>
				</div>
			</b:includable>
  <b:includable id='postQuickEdit' var='post'>
				<b:if cond='data:post.editUrl'>
					<span expr:class='&quot;item-control &quot; + data:post.adminClass'>
						<a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
							<img alt='' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
						</a>
					</span>
				</b:if>
			</b:includable>
  <b:includable id='shareButtons' var='post'>
				<b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'>
				<span class='share-button-link-text'><data:top.emailThisMsg/></span>
				</a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'>
				<span class='share-button-link-text'><data:top.blogThisMsg/></span>
				</a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'>
				<span class='share-button-link-text'><data:top.shareToTwitterMsg/></span>
				</a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'>
				<span class='share-button-link-text'><data:top.shareToFacebookMsg/></span>
				</a></b:if><b:if cond='data:top.showOrkutButton'><a class='goog-inline-block share-button sb-orkut' expr:href='data:post.sharePostUrl + &quot;&amp;target=orkut&quot;' expr:title='data:top.shareToOrkutMsg' target='_blank'>
				<span class='share-button-link-text'><data:top.shareToOrkutMsg/></span>
				</a></b:if><b:if cond='data:top.showBuzzButton'><a class='goog-inline-block share-button sb-buzz' expr:href='data:post.sharePostUrl + &quot;&amp;target=buzz&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=415,width=690\&quot;); return false;&quot;' expr:title='data:top.shareToBuzzMsg' target='_blank'>
				<span class='share-button-link-text'><data:top.shareToBuzzMsg/></span>
				</a></b:if>
				<b:if cond='data:top.showDummy'>
					<div class='goog-inline-block dummy-container'><data:post.dummyTag/></div>
				</b:if>
			</b:includable>
  <b:includable id='status-message'>
				<b:if cond='data:navMessage'>
					<div class='status-msg-wrap'>
						<div class='status-msg-body'>
							<data:navMessage/>
						</div>
						<div class='status-msg-border'>
							<div class='status-msg-bg'>
								<div class='status-msg-hidden'><data:navMessage/></div>
							</div>
						</div>
					</div>
					<div style='clear: both;'/>
				</b:if>
			</b:includable>
  <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' expr:height='data:cmtIframeInitialHeight' frameborder='0' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;);
    </script>
  </div>
</b:includable>
  <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
  <b:includable id='threaded_comments' var='post'>
  <div class='comments' id='comments'>
    <a name='comments'/>
    <h4><data:post.commentLabelFull/>:</h4>

    <div class='comments-content'>
      <b:include cond='data:post.embedCommentForm' data='post' name='threaded_comment_js'/>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
      <b:include cond='data:post.showBacklinks' data='post' name='backlinks'/>
    </div>
    </div>
  </div>
</b:includable>
</b:widget>
</b:section>
<!-- // content -->
</div>
<div id='sidebar'>
    <div class='sponsors empty'>
        <!-- TLS class="empty" F-FDTL script MEDIA -->
    </div>
	<div class='sponsors-after'>
	<h2>F-FDTL</h2>
	<p>TIMOR-LESTE <a href='mailto:sponsorship@coscup.org'>sponsorship@coscup.org</a> 聯絡&#12290;</p>
	</div>
</div>
<div id='footer'>
    <div class='info'>
        <p id='copyright'> 2016 F-FDTL<a href='http://coscup.org/2011/zh-tw/contact/'>P I</a>&#12290;</p>
        <p id='tagline'>We <span class='heart'>(heart)</span> Open.</p>
        <p id='archives'>
            <a href='http://coscup.org/2006/'>2006</a>
            <span class='separator'> | </span><a href='http://coscup.org/2007/'>2007</a>
            <span class='separator'> | </span><a href='http://coscup.org/2008/'>2008</a>
            <span class='separator'> | </span><a href='http://coscup.org/2009/'>2009</a>
            <span class='separator'> | </span><a href='http://coscup.org/2010/'>2010</a>
        </p>
    </div>
</div>
<script src='http://ajax.googleapis.com/ajax/libs/jquery/1.5/jquery.min.js' type='text/javascript'/>
<script src='http://coscup.org/2011-theme/assets/script.min.js' type='text/javascript'/>
</body>
</html>
