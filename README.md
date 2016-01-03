[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=K4CMP92RZELE2)

Eclipse Java Code Formatter for NetBeans
========================================

This NetBeans plugin helps you to apply to a common code style in a team of Eclipse JDT and NetBeans IDE users. The original formatting engine of Eclipse is embedded and allows you to format the sourcecode the same way as your Eclipse co-workers do. You only have to provide a Eclipse formatter configuration file.

Download available at http://plugins.netbeans.org/plugin/50877/?show=true

----

Cloned from https://java.net/projects/nb-api-samples/sources/api-samples/show/versions/7.3/misc/EclipseFormatter

See original documentation at 
* https://blogs.oracle.com/geertjan/entry/eclipse_formatter_for_netbeans_ide
* https://blogs.oracle.com/geertjan/entry/eclipse_formatter_for_netbeans_ide1

---- 


This plugin helps you to apply to a common code style in a team of Eclipse JDT and NetBeans IDE users. The original formatting engine of Eclipse is embedded and allows you to format the sourcecode the same way as your Eclipse co-workers do. You only have to provide an Eclipse formatter configuration file.
<h3>
<font color="#FF0000">Known issue: When the Eclipse formatter is used the line-breakpoints at the formatted lines are lost. Class/Method/Field breakpoints will be preserved.</font>
</h3>
<h2>Features:</h2>
<ul>
<li>Global configuration and project specific configuration</li>
<li>Supports profiles (since 1.6)</li>
<li>On save action (Disabled by default)</li>
<li>Shows the used formatter as notification  (Enabled by default)</li>
<li>Supports format of selected text (since 1.7)</li>
<li>Preserve breakpoints (experimental) (since 1.8)</li>
<li>Code templates for @formatter:on/off (since 1.9)</li>
</ul>

<h2>Updates in 1.9:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/63">Task 63</a>]: Update to Eclipse formatter jars from Eclipse 4.5.1 (Mars.1)</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/65">Feature 65</a>]: Code templates for @formatter:on/off (<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/wiki/Support-of-@formatter:off">More details...)</a></li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/66">Task 66</a>]: Update requirements to NetBeans 8.0+</li>

</ul>
<h2>Updates in 1.8.0.6:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/57">Bugfix 57</a>]: Fixed: java.lang.IllegalArgumentException: bad position and run parts in EDT</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/4">Bugfix 4</a>]: Fixed: option panel isn't found by searching for "eclipse"</li>
</ul>
<h2>Updates in 1.8.0.5:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/56">Bugfix 56</a>]: Fixed: Format on Save - Changed files remain modified after saving them in Java Editor </li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/55">Bugfix 55</a>]: Fixed: "URI is not hierarchical" error message on calling format - add logging for this error</li>
</ul>
<h2>Updates in 1.8.0.4:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/47">Feature 47</a>]: Preserve Class/Method/Field breakpoints (experimental, can be disabled in options)</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/47">Bugfix 53</a>]: Fixed: Do not remove linebreakpoint, if line is not included in selection</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/52">Bugfix 52</a>]: Fixed: Cannot assign shortcut for "Format with Eclipse Formatter" action</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/46">Task 46</a>]: Update to use eclipse formatter libs from eclipse 4.4 </li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/48">Task 48</a>]: Support only NetBeans 7.4 and above</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/49">Task 49</a>]: Add donation button</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/50">Task 50</a>]: Add link to github/homepage</li>

</ul>
<h2>Updates in 1.7.1:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/41">Bugfix 41</a>]: Fixed: NPE when configuration file not found </li>
</ul>
<h2>Updates in 1.7:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/pull/38">Feature 38</a>]: Format selected part of document (PR by <a href="https://github.com/saadmufti">saadmufti</a>)</li>
</ul>
<h2>Updates in 1.6.1:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/34">Bugfix 34</a>]: Fixed: NPE while saving options when no profile is set</li>
</ul>
<h2>Updates in 1.6:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/30">Task 30</a>]: Update to Eclipse formatter jars from Eclipse Kepler 4.3</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/31">Feature 31</a>]: First profile in file is always used - support selection of profile</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/21">Feature 21</a>]: Project specific options: Show link to global options</li>
</ul>

<h2>Updates in 1.5:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/18">Bugfix 18</a>]: Fixed: Formatting with eclipse formatter introduces empty document in undo manager</li>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/27">Task 27</a>]: Provide a signed package for the PPUC</li>
</ul>

<h2>Updates in 1.4.1:</h2>
<ul>
<li>[<a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues/25">Bugfix 25</a>]: Fixed: Configured formatter.xml isn't used</li>
</ul>
<h2>Updates in 1.4:</h2>
<ul>
<li>major refactorings and fixes - see <a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues?milestone=1&page=1&state=closed">milestone 1.4@github</a></li>
</ul>
<h2>Note:</h2>
Please note that this plugin only provides support for formatting. Eclipse users may miss the application of save-actions like "adding @Override annotations" or "member sort order". Such AST-based transformations are not provided by this plugin. The plugin also won't format source code with guarded sections - like the Java sources generated by the NetBeans GUI builder.

<h2>Licensing</h2>
<ul>
<li>This plugin is licensed under <a href="http://www.eclipse.org/legal/epl-v10.html">Eclipse Public License, Version 1.0</a>
</li>
<li>This plugin bundles several 3rd-party libraries to provide its functionality.
<dl><dt><a href="http://www.eclipse.org/legal/epl-v10.html">Eclipse Public License, Version 1.0</a></dt><dd>
org.eclipse.core.contenttype_3.5.0.v20150421-2214.jar
org.eclipse.core.jobs_3.7.0.v20150330-2103.jar
org.eclipse.core.resources_3.10.1.v20150725-1910.jar
org.eclipse.core.runtime_3.11.1.v20150903-1804.jar
org.eclipse.equinox.common_3.7.0.v20150402-1709.jar
org.eclipse.equinox.preferences_3.5.300.v20150408-1437.jar
org.eclipse.jdt.core_3.11.1.v20150902-1521.jar
org.eclipse.text_3.5.400.v20150505-1044.jar
</dd>
</dl>
<dl><dt><a href="http://www.apache.org/licenses/LICENSE-2.0.txt">Apache License, Version 2.0</a></dt><dd>commons-beanutils-1.8.3.jar
commons-digester3-3.2.jar
commons-logging-1.1.3.jar</dd>
</dl>
</li>
<li>Originally forked from <a href="https://blogs.oracle.com/geertjan/entry/eclipse_formatter_for_netbeans_ide">https://blogs.oracle.com/geertjan/entry/eclipse_formatter_for_netbeans_ide</a> with allowance of Geertjan Wielenga.</li>
<li>Based on <a href="http://epochcoder.blogspot.com/2013/08/import-eclipse-formatter-into-netbeans.html">http://epochcoder.blogspot.com/2013/08/import-eclipse-formatter-into-netbeans.html</a> from Willie Scholtz.</li>
</ul>

<p>
Provide defects, request for enhancements and feedback at <a href="https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues">https://github.com/markiewb/eclipsecodeformatter_for_netbeans/issues</a>
</p>
Compatible to NetBeans 8.0.2+ and JDK7+.

<p>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=K4CMP92RZELE2"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_SM.gif" alt="btn_donate_SM.gif"></a>

</p>



