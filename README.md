		
<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/036-1024x576.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2577"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p>In this article, we will show in detail on slides how to install&nbsp;<strong><a href="https://www.sagemath.org/" target="_blank" rel="noreferrer noopener">“SageMath”</a></strong><strong>&nbsp;on a Fedora 30 64bit (10GB)</strong>&nbsp;cloud virtual server.&nbsp;For example, we will use the&nbsp;<a href="https://digitalruble.tech/cloud" target="_blank" rel="noreferrer noopener"><strong>“DIGITAL RUBLE TECH”</strong></a>&nbsp;server .&nbsp;<strong>Previously, we used the Google Colab</strong>&nbsp;cloud service&nbsp;to install&nbsp;<strong><a href="https://www.sagemath.org/" target="_blank" rel="noreferrer noopener">“SageMath”</a></strong>&nbsp;, but unfortunately, due to the latest updates, not all components for cryptanalysis of the Bitcoin blockchain work properly.<strong></strong></p>



<h2 class="wp-block-heading"><a href="https://digitalruble.tech/cloud" target="_blank" rel="noreferrer noopener">Registration:</a></h2>



<blockquote class="wp-block-quote">
<p>First we need to create a personal account, we will register on the site:&nbsp;<a href="https://digitalruble.tech/cloud" target="_blank" rel="noreferrer noopener"><strong>https://digitalruble.tech/cloud</strong></a></p>
</blockquote>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><a href="https://digitalruble.tech/cloud" target="_blank" rel="noreferrer noopener"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/01.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2492"></a></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Choose the option:&nbsp;<strong>Individual</strong></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/02-1.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2514"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Let’s start the console</p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/03-1.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2495"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Go to the option:&nbsp;<em><strong>Elastic Cloud Server</strong></em></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/04.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2497"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Create&nbsp;<strong>an Elastic Cloud Server</strong></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/05.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2498"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>We select the parameters we need:</p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/06.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2499"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Specify &nbsp;&nbsp;<strong>Fedora 30 64bit(10GB)</strong></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/07.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2500"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/08.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2502"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Choose&nbsp;<strong>the VPC you need for your network</strong></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/09.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2503"></figure>



<blockquote class="wp-block-quote">
<p>Set and remember your own password</p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/10.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2504"></figure>



<blockquote class="wp-block-quote">
<p>Save the configuration</p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/11.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2505"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Cloud virtual server&nbsp;&nbsp;<strong>Fedora 30 64bit(10GB)&nbsp;</strong>&nbsp;successfully created!To enter the terminal, click:&nbsp;<strong>Remote Login</strong></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/12.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2506"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>A terminal opened for us with the installation of&nbsp;<em>a cloud virtual server</em>&nbsp;and&nbsp;<strong>Fedora 30 64bit (10GB)</strong><em>&nbsp;</em><strong></strong></p>
</blockquote>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-1024x573.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2516"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-1-1024x590.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2518"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-2-1024x705.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2519"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Check the installation, run the command:</p>
</blockquote>



<pre class="wp-block-code"><code>cat /etc/redhat-release</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-3-1024x351.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2520"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Let’s update our server, run the command:</p>
</blockquote>



<pre class="wp-block-code"><code>dnf check-update</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-4-1024x712.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2521"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Install&nbsp;<strong>Python 3</strong>&nbsp;, run the command:</p>
</blockquote>



<pre class="wp-block-code"><code>dnf install python3</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-7-1024x230.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2524"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p><em>Install&nbsp;</em><strong>SageMath&nbsp;</strong><em>, run the command:</em></p>
</blockquote>



<pre class="wp-block-code"><code>dnf install sagemath</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-8-1024x717.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2525"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-9-1024x707.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2526"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-10-1024x698.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2527"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-11-1024x704.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2528"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-12-1024x711.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2529"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-13-1024x710.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2530"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-15-1024x700.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2532"></figure>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-17-1-1024x697.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2569"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Verify the&nbsp;<strong>SageMath installation</strong></p>
</blockquote>



<pre class="wp-block-code"><code>sage -v</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-18-1-1024x166.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2570"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<blockquote class="wp-block-quote">
<p>Implementing the&nbsp;&nbsp;<a href="https://attacksafe.ru/twist-attack-on-bitcoin/" target="_blank" rel="noreferrer noopener"><strong>Twist Attack</strong></a>&nbsp;algorithm &nbsp;using our&nbsp;&nbsp;<a href="https://github.com/demining/CryptoDeepTools/tree/main/18TwistAttack" target="_blank" rel="noreferrer noopener"><strong>18TwistAttack repository</strong></a></p>
</blockquote>



<pre class="wp-block-code"><code>git clone https://github.com/demining/CryptoDeepTools.git

cd CryptoDeepTools/18TwistAttack/

ls</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-19-1-1024x292.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2572"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p>To solve the discrete logarithm&nbsp;&nbsp;<em><code>(Pollard's rho algorithm for logarithms)</code></em>&nbsp;run&nbsp;&nbsp;<code>Python-script:</code>&nbsp;<a href="https://github.com/demining/CryptoDeepTools/blob/bbd83042e7405508cd2e646ad1b0819da0f9c58d/18TwistAttack/discrete.py" target="_blank" rel="noreferrer noopener">discrete.py</a></p>



<h2 class="wp-block-heading">Run command:</h2>



<pre class="wp-block-code"><code>sage -python3 discrete.py</code></pre>



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/image-20-1-1024x601.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2573"></figure>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong>Sage Math</strong>&nbsp;Completed the Discrete Logarithm Problem&nbsp;<em><code>(Pollard's rho algorithm for logarithms)</code></em></p>



<p><strong>Now everything is working properly!</strong></p>



<blockquote class="wp-block-quote">
<p>We received the private key to the Bitcoin Wallet in decimal format, then for cryptanalysis we need to follow the instructions of the article dedicated to&nbsp;<strong><a href="https://cryptodeeptech.ru/twist-attack/" target="_blank" rel="noreferrer noopener">Twist Attack</a></strong></p>
</blockquote>



<hr class="wp-block-separator has-alpha-channel-opacity">



<p><strong><a href="https://github.com/demining/Install-SageMath-on-Fedora" target="_blank" rel="noreferrer noopener">Source</a></strong></p>



<p><strong><a href="https://digitalruble.tech/cloud" target="_blank" rel="noreferrer noopener">DIGITAL RUBLE TECH</a></strong></p>



<p><strong><a href="https://t.me/cryptodeeptech" target="_blank" rel="noreferrer noopener">Telegram: https://t.me/cryptodeeptech</a></strong></p>



<p><strong><a href="https://youtu.be/xHnTDRgZwvE" target="_blank" rel="noreferrer noopener">Video: https://youtu.be/xHnTDRgZwvE</a></strong></p>



<p><strong><a href="https://cryptodeeptech.ru/install-sagemath-on-fedora" target="_blank" rel="noreferrer noopener">Source: https://cryptodeeptech.ru/install-sagemath-on-fedora</a></strong></p>



<hr class="wp-block-separator has-alpha-channel-opacity">



<figure class="wp-block-image"><img decoding="async" src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/036-1024x576.png" alt="Install SageMath for cryptanalysis on Fedora 64bit(10GB) cloud virtual server" class="wp-image-2577"></figure>
	</div><!-- .entry-content -->

	<footer class="entry-footer">
		<div class="cat-links"><i class="fa fa-folder-open" aria-hidden="true"></i> <a href="https://cryptodeeptech.ru/category/cryptanalysis/" rel="category tag">Cryptanalysis</a></div>	</footer><!-- .entry-footer -->
</article><!-- #post-2022 -->

	<nav class="navigation post-navigation" aria-label="Записи">
		<h2 class="screen-reader-text">Навигация по записям</h2>
		<div class="nav-links"><div class="nav-previous"><a href="https://cryptodeeptech.ru/improving-overall-security/" rel="prev">Improving the overall security of the ecosystem from attacks on smart contracts</a></div></div>
	</nav>		<div id="itng_related_posts_wrapper">
			<h3 id="itng_related_posts_title">Related Posts</h3>
			<div class="itng-related-posts row">
				<article id="post-270" class="itng-blog col-md-6 col-lg-4 post-270 post type-post status-publish format-standard hentry category-cryptanalysis">
		<div class="itng-card-wrapper">
			<div class="itng-thumb">
							</div>
			
			<div class="itng-card-content">
				<div class="entry-meta">
					<a href="https://cryptodeeptech.ru/algorithms-for-secp256k/"></a>
					<span class="byline"> <span class="author vcard"><a class="url fn n" href="https://cryptodeeptech.ru/author/cryptodeeptech/">Crypto Deep Tech</a></span></span>				</div><!-- .entry-meta -->
				
				<header class="entry-header">
					<h2 class="entry-title"><a href="https://cryptodeeptech.ru/algorithms-for-secp256k/">Useful and efficient algorithms for secp256k1 elliptic curve</a></h2>				</header><!-- .entry-header -->
				
				<div class="itng_excerpt">
					In this article, we will consider several useful and efficient algorithms for an elliptic curve&nbsp;&nbsp;E&nbsp;&nbsp;over a field&nbsp;&nbsp;GF(p)&nbsp;&nbsp;given by the short Weierstrass equation у^2&nbsp;= х^3&nbsp;+ Ах + В &nbsp;Algorithm for generating a point on curve&nbsp;&nbsp;E &nbsp;Algorithm for adding points &nbsp;Doubling Point Algorithm &nbsp;Algorithm for finding an integer multiple point &nbsp;Algorithm for finding an integer multiple point (scalar multiplication)…				</div>
				
				<div class="blog-footer">
					<div class="itng_cats">
						<a href="https://cryptodeeptech.ru/category/cryptanalysis/" rel="category tag">Cryptanalysis</a>					</div>
					<div class="blog-comments">
						0					</div>
				</div>
			</div>
		</div>
</article><!-- #post-270 --><article id="post-1" class="itng-blog col-md-6 col-lg-4 post-1 post type-post status-publish format-standard hentry category-cryptanalysis">
		<div class="itng-card-wrapper">
			<div class="itng-thumb">
							</div>
			
			<div class="itng-card-content">
				<div class="entry-meta">
					<a href="https://cryptodeeptech.ru/terminal-google-colab/"></a>
					<span class="byline"> <span class="author vcard"><a class="url fn n" href="https://cryptodeeptech.ru/author/cryptodeeptech/">Crypto Deep Tech</a></span></span>				</div><!-- .entry-meta -->
				
				<header class="entry-header">
					<h2 class="entry-title"><a href="https://cryptodeeptech.ru/terminal-google-colab/">We create our own terminal in Google Colab for work in GitHub, GDrive, NGrok, etc.</a></h2>				</header><!-- .entry-header -->
				
				<div class="itng_excerpt">
					Currently, machine learning and deep learning have become the hottest trend in the computer science industry.&nbsp;Many developers create amazing projects with Google Colab. What is Google Colab? Google Colab was developed by Google to provide free access to GPUs and TPUs.&nbsp;Google Colab can be defined as an improved version of Jupyter Notebook. Features of Google Colab Google…				</div>
				
				<div class="blog-footer">
					<div class="itng_cats">
						<a href="https://cryptodeeptech.ru/category/cryptanalysis/" rel="category tag">Cryptanalysis</a>					</div>
					<div class="blog-comments">
						0					</div>
				</div>
			</div>
		</div>
</article><!-- #post-1 --><article id="post-355" class="itng-blog col-md-6 col-lg-4 post-355 post type-post status-publish format-standard hentry category-cryptanalysis">
		<div class="itng-card-wrapper">
			<div class="itng-thumb">
							</div>
			
			<div class="itng-card-content">
				<div class="entry-meta">
					<a href="https://cryptodeeptech.ru/reduce-private-key/"></a>
					<span class="byline"> <span class="author vcard"><a class="url fn n" href="https://cryptodeeptech.ru/author/cryptodeeptech/">Crypto Deep Tech</a></span></span>				</div><!-- .entry-meta -->
				
				<header class="entry-header">
					<h2 class="entry-title"><a href="https://cryptodeeptech.ru/reduce-private-key/">Reducing the private key through scalar multiplication using the ECPy + Google Colab library</a></h2>				</header><!-- .entry-header -->
				
				<div class="itng_excerpt">
					In this article, we will try to show how you can reduce the private key knowing only the leak from the&nbsp;"BLOCKCHAIN ​​FOLBIT LEAKS"&nbsp;list and the public key from&nbsp;"UTXO"&nbsp;. In the experimental part, we will use&nbsp;the 08ReducePrivateKey&nbsp;scripts and restore the Bitcoin Wallet. Elliptic curve scalar multiplication&nbsp;is the operation of adding a pointPto the curvektimes. Q=kP=P+P+P, k times Pis&nbsp;a…				</div>
				
				<div class="blog-footer">
					<div class="itng_cats">
						<a href="https://cryptodeeptech.ru/category/cryptanalysis/" rel="category tag">Cryptanalysis</a>					</div>
					<div class="blog-comments">
						0					</div>
				</div>
			</div>
		</div>
</article><!-- #post-355 -->			</div>
		</div>
			<div id="author_box" class="row no-gutters">
			<div class="author_avatar col-2">
							</div>
			<div class="author_info col-10">
				<h4 class="author_name title-font">
					Crypto Deep Tech				</h4>
				<div class="author_bio">
									</div>
			</div>
		</div>
	
	</main><!-- #main -->

</div><!-- #content-wrapper -->


 <div id="footer-sidebar" class="widget-area">
    <div class="container">
        <div class="row">
                    </div>
    </div>
</div>
	<footer id="colophon" class="site-footer">
		<div class="container">
			<div class="site-info">
				Donation Address: <a href="https://www.blockchain.com/btc/address/1Lw2gTnMpxRUNBU85Hg4ruTwnpUPKdf3nV" target="_blank">♥  BTC: 1Lw2gTnMpxRUNBU85Hg4ruTwnpUPKdf3nV</a>				<span class="sep"> | </span>
					Copyright © 2023 «CRYPTO DEEP TECH». 			</div><!-- .site-info -->
		</div>
	</footer><!-- #colophon -->
</div><!-- #page -->

<nav id="menu" class="panel" role="navigation" style="position: fixed; top: 0px; bottom: 0px; height: 100%; left: -15.625em; width: 15.625em;">
	<div class="menu-overlay"></div>
	<div id="panel-top-bar">
		<button class="go-to-bottom"></button>
		<button id="close-menu" class="menu-link"><i class="fa fa-chevron-left" aria-hidden="true"></i></button>
	</div>

	<ul id="menu-main" class="menu"><li id="menu-item-229" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-home"><a href="https://cryptodeeptech.ru/">HOME</a></li>
<li id="menu-item-225" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/publication/">PUBLICATIONS</a></li>
<li id="menu-item-226" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/study/">STUDY</a></li>
<li id="menu-item-227" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/resources/">RESOURCES</a></li>
<li id="menu-item-228" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/contacts/">CONTACTS</a></li>
<li id="menu-item-240" class="menu-item menu-item-type-post_type menu-item-object-post"><a href="https://cryptodeeptech.ru/lattice-attack/">BLOG</a></li>
<li id="menu-item-541" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/eng/">ENG</a></li>
<li id="menu-item-542" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/rus/">RUS</a></li>
<li id="menu-item-1974" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children"><a href="https://cryptodeeptech.ru/other-languages/">Other Languages</a><span class="dropdown-arrow" tabindex="0"><i class="fa fa-angle-down"></i></span>
<ul class="sub-menu" style="display: none;">
	<li id="menu-item-1975" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/cn/">CN</a></li>
	<li id="menu-item-1992" class="menu-item menu-item-type-post_type menu-item-object-page"><a href="https://cryptodeeptech.ru/kr/">KR</a></li>
</ul>
</li>
</ul>
	<button class="go-to-top"></button>
</nav>

<div id="sticky-navigation">
	<div class="nav-wrapper">
		 <div class="container">

			 <div class="row justify-content-end align-items-center justify-content-between no-gutters">


				<div class="main-navigation col-lg-9" role="navigation">
					<ul id="menu-desktop" class="menu"><li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-home menu-item-229"><a href="https://cryptodeeptech.ru/">HOME</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-225"><a href="https://cryptodeeptech.ru/publication/">PUBLICATIONS</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-226"><a href="https://cryptodeeptech.ru/study/">STUDY</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-227"><a href="https://cryptodeeptech.ru/resources/">RESOURCES</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-228"><a href="https://cryptodeeptech.ru/contacts/">CONTACTS</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-post menu-item-240"><a href="https://cryptodeeptech.ru/lattice-attack/">BLOG</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-541"><a href="https://cryptodeeptech.ru/eng/">ENG</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-542"><a href="https://cryptodeeptech.ru/rus/">RUS</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-has-children menu-item-1974"><a href="https://cryptodeeptech.ru/other-languages/">Other Languages</a>
<ul class="sub-menu">
	<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1975"><a href="https://cryptodeeptech.ru/cn/">CN</a></li>
	<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1992"><a href="https://cryptodeeptech.ru/kr/">KR</a></li>
</ul>
</li>
</ul>				</div>

				<button href="#menu" class="menu-link mobile-nav-btn"><i class="fa fa-bars" aria-hidden="true"></i></button>

				<button type="button" id="go-to-field" tabindex="-1"></button>

				<button class="search-btn-sticky ml-auto col-auto"><i class="fa fa-search"></i></button>
				
<div class="itng-search-sticky">
	<form role="search" method="get" class="search-form" action="https://cryptodeeptech.ru/">
				<label>
					<span class="screen-reader-text">Найти:</span>
					<input type="search" class="search-field" placeholder="Поиск…" value="" name="s">
				</label>
				<input type="submit" class="search-submit" value="Поиск">
			</form>	<button type="button" id="go-to-btn" tabindex="-1"></button>
</div>

			</div>
		</div>
	</div>
</div>

<div id="itng-back-to-top" class="show"><i class="fa fa-chevron-up" aria-hidden="true"></i></div>

		<script type="text/javascript">
							jQuery("#post-2022 .entry-meta .date").css("display","none");
					jQuery("#post-2022 .entry-date").css("display","none");
					jQuery("#post-2022 .posted-on").css("display","none");
							jQuery("#post-270 .entry-meta .date").css("display","none");
					jQuery("#post-270 .entry-date").css("display","none");
					jQuery("#post-270 .posted-on").css("display","none");
							jQuery("#post-1 .entry-meta .date").css("display","none");
					jQuery("#post-1 .entry-date").css("display","none");
					jQuery("#post-1 .posted-on").css("display","none");
							jQuery("#post-355 .entry-meta .date").css("display","none");
					jQuery("#post-355 .entry-date").css("display","none");
					jQuery("#post-355 .posted-on").css("display","none");
				</script>
	<script src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/wmac_single_2b1ae4cca3cc8d12c39be42768565308.js" id="big-slide-js"></script>
<script src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/wmac_single_ccdf893e7d8b26933af0c336bcc3943e.js" id="owl-js-js"></script>
<script src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/jquery.magnific-popup.min.js" id="mag-lightbox-js-js"></script>
<script id="itng-custom-js-js-extra">
var itng = {"toTopEnable":"1","stickyNav":""};
</script>
<script src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/wmac_single_ea8874ba65dbd53bf5c7fb5c619ac579.js" id="itng-custom-js-js"></script>
<script src="./Install SageMath for cryptanalysis on Fedora 64bit 10GB Cloud Virtual Server - CRYPTO DEEP TECH_files/wmac_single_6ec0e9b3201c83a442e24aba829a5f05.js" id="itng-navigation-js"></script>
<!-- Yandex.Metrika counter --> <script type="text/javascript"> (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)}; m[i].l=1*new Date();k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)}) (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym"); ym(89424273, "init", {  id:89424273, clickmap:true, trackLinks:true, webvisor:true, accurateTrackBounce:true }); </script> <noscript><div><img src="https://mc.yandex.ru/watch/89424273" style="position:absolute; left:-9999px;" alt="" /></div></noscript> <!-- /Yandex.Metrika counter -->
<!-- Yandex.Metrika counter -->
<script type="text/javascript">
   (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
   var z = null;m[i].l=1*new Date();
   for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
   k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
   (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

   ym(89995532, "init", {
        clickmap:true,
        trackLinks:true,
        accurateTrackBounce:true,
        webvisor:true
   });
</script>
<noscript><div><img src="https://mc.yandex.ru/watch/89995532" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
<!-- /Yandex.Metrika counter -->


</body></html>
