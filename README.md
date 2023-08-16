<h1>MinimalistConky v1.3.3 Configuration</h1>

<p><img src="https://github.com/SnowballTheLev/MinimalistConky/blob/main/screenshot-w.png" alt="MinimalistConky Screenshot-1" width="49.5%" height="50%"> <img src="https://github.com/SnowballTheLev/MinimalistConky/blob/main/screenshot-b.png" alt="MinimalistConky Screenshot-2" width="49.5%" height="50%"></p>

<p><a href="https://github.com/SnowballTheLev/MinimalistConky">MinimalistConky</a> is a lightweight, simple and minimalistic <a href="https://github.com/brndnmtthws/conky">conky</a> configuration that provides system information and task monitoring on your <a href="https://gitlab.xfce.org/public">Xfce</a> desktop. It features clean and simple design, and easy setup.</p>

<h2>Features</h2>

<ul>
  <li>Display system information like <a href="https://github.com/dylanaraps/neofetch">neofetch</a>.</li>
  <li>Monitor CPU usage, memory usage, and disk usage, running tasks and their resource utilization like <a href="https://www.opencode.net/deny26/minimalis-conky-2">Minimalis Conky 2</a>.</li>
  <li>Customizable appearance with simple and minimalist design.</li>
  <li>Included <code>.desktop</code> file for easy access and a shell script to start <a href="https://github.com/brndnmtthws/conky">conky</a>.</li>
</ul>

<h2>Preview</h2>

<p><img src="https://github.com/SnowballTheLev/MinimalistConky/blob/main/screenshot-sysinfo.png" alt="MinimalistConky 'sysinfo' Preview" width="30%" height="30%"> <img src="https://github.com/SnowballTheLev/MinimalistConky/blob/main/screenshot-taskmgr.png" alt="MinimalistConky 'taskmgr' Preview" width="24.65%" height="30%"></p>

<h2>Prerequisites</h2>

<ul>
  <li><a href="https://github.com/gitGNU">GNU</a>/<a href="https://github.com/torvalds/linux">Linux</a> with <a href="https://www.x.org/wiki/">X Window System</a> (X11) and <a href="https://gitlab.xfce.org/public">Xfce</a> DE (tested only on <a href="https://www.debian.org/distrib/">Debian 12</a> with <a href="https://xfce.org/download">Xfce 4.18.1</a>).</li>
  <li><a href="https://github.com/brndnmtthws/conky">conky</a> and <a href="https://github.com/Conservatory/wmctrl">wmctrl</a> (for the number of the currently active virtual desktop) installed (usually available through your distribution's package manager).</li>
</ul>

<h2>Installation</h2>

<ol>
  <li>Clone this repository to your desired location and move its contents to <code>$HOME/.config/conky</code>:</li>
</ol>

<pre><code>git clone https://github.com/SnowballTheLev/MinimalistConky.git
mv /path/to/MinimalistConky/* $HOME/.config/conky/
cd $HOME/.config/conky/
</code></pre>

<ol start="2">
  <li>Make the shell script executable:</li>
</ol>

<pre><code>chmod +x start-conky
</code></pre>

<ol start="3">
  <li>Customize the configuration files <code>sysinfo-conky.conf</code> and <code>taskmgr-conky.conf</code> according to your preferences. Add included <code>ConkySymbols.ttf</code> to <code>$HOME/.local/share/fonts</code> for Icon.</li>
  <li>Run conky using the provided shell script:</li>
</ol>

<pre><code>./start-conky
</code></pre>

<h2>Customization</h2>

<p>Open and edit the <code>sysinfo-conky.conf</code> and <code>taskmgr-conky.conf</code> files to modify the displayed information and tweak the appearance. You can change fonts, colors, and positions to match your desktop theme.</p>

<h2>Usage</h2>

<ul>
  <li>Move the included <code>.desktop</code> file to <code>$HOME/.config/autostart</code> to start <a href="https://github.com/SnowballTheLev/MinimalistConky">MinimalistConky</a> on login.</li>
  <li>Alternatively, you can run the <code>start-conky</code> script from the terminal.</li>
</ul>

<h2>Credits</h2>

<p>This project is inspired by the <a href="https://github.com/dylanaraps/neofetch">neofetch</a> and <a href="https://www.opencode.net/deny26/minimalis-conky-2">Minimalis Conky 2</a>.</p>
<p>Icon : <a href="https://github.com/SnowballTheLev/MinimalistConky/blob/main/ConkySymbols.ttf">ConkySymbols</a> (form <a href="https://www.opencode.net/deny26/minimalis-conky-2">Minimalis Conky 2</a>)</p>

<h2>License</h2>

<p>This project is licensed under the <a href="https://github.com/SnowballTheLev/MinimalistConky/blob/main/LICENSE">GPL License</a>.</p>
