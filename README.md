		
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
