---
layout: api
class: MarkdownExtra_Parser
---
<h1>MarkdownExtra_Parser</h1>
extends <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>
<br />
<p>
<i>
</i>
</p>
<div class='toc row d-none d-sm-flex d-md-flex d-lg-flex d-xl-flex'>
<div class='constants col-4'>
<h3>Constants</h3>
<ul>
<li>
<em>None</em>
</li>
</ul>
</div>
<div class='properties col-4'>
<h3>Properties</h3>
<ul>
<li>
<a href="#property-abbr_desciptions">$abbr_desciptions</a>
</li>
<li>
<a href="#property-abbr_word_re">$abbr_word_re</a>
</li>
<li>
<a href="#property-auto_close_tags_re">$auto_close_tags_re</a>
</li>
<li>
<a href="#property-block_gamut">$block_gamut</a>
</li>
<li>
<a href="#property-block_tags_re">$block_tags_re</a>
</li>
<li>
<a href="#property-clean_tags_re">$clean_tags_re</a>
</li>
<li>
<a href="#property-contain_span_tags_re">$contain_span_tags_re</a>
</li>
<li>
<a href="#property-context_block_tags_re">$context_block_tags_re</a>
</li>
<li>
<a href="#property-document_gamut">$document_gamut</a>
</li>
<li>
<a href="#property-em_relist">$em_relist</a>
</li>
<li>
<a href="#property-em_strong_prepared_relist">$em_strong_prepared_relist</a>
</li>
<li>
<a href="#property-em_strong_relist">$em_strong_relist</a>
</li>
<li>
<a href="#property-empty_element_suffix">$empty_element_suffix</a>
</li>
<li>
<a href="#property-escape_chars">$escape_chars</a>
</li>
<li>
<a href="#property-escape_chars_re">$escape_chars_re</a>
</li>
<li>
<a href="#property-fn_backlink_class">$fn_backlink_class</a>
</li>
<li>
<a href="#property-fn_backlink_title">$fn_backlink_title</a>
</li>
<li>
<a href="#property-fn_id_prefix">$fn_id_prefix</a>
</li>
<li>
<a href="#property-fn_link_class">$fn_link_class</a>
</li>
<li>
<a href="#property-fn_link_title">$fn_link_title</a>
</li>
<li>
<a href="#property-footnote_counter">$footnote_counter</a>
</li>
<li>
<a href="#property-footnotes">$footnotes</a>
</li>
<li>
<a href="#property-footnotes_ordered">$footnotes_ordered</a>
</li>
<li>
<a href="#property-html_hashes">$html_hashes</a>
</li>
<li>
<a href="#property-in_anchor">$in_anchor</a>
</li>
<li>
<a href="#property-list_level">$list_level</a>
</li>
<li>
<a href="#property-nested_brackets_depth">$nested_brackets_depth</a>
</li>
<li>
<a href="#property-nested_brackets_re">$nested_brackets_re</a>
</li>
<li>
<a href="#property-nested_url_parenthesis_depth">$nested_url_parenthesis_depth</a>
</li>
<li>
<a href="#property-nested_url_parenthesis_re">$nested_url_parenthesis_re</a>
</li>
<li>
<a href="#property-no_entities">$no_entities</a>
</li>
<li>
<a href="#property-no_markup">$no_markup</a>
</li>
<li>
<a href="#property-predef_abbr">$predef_abbr</a>
</li>
<li>
<a href="#property-predef_titles">$predef_titles</a>
</li>
<li>
<a href="#property-predef_urls">$predef_urls</a>
</li>
<li>
<a href="#property-span_gamut">$span_gamut</a>
</li>
<li>
<a href="#property-strong_relist">$strong_relist</a>
</li>
<li>
<a href="#property-tab_width">$tab_width</a>
</li>
<li>
<a href="#property-titles">$titles</a>
</li>
<li>
<a href="#property-urls">$urls</a>
</li>
<li>
<a href="#property-utf8_strlen">$utf8_strlen</a>
</li>
</ul>
</div>
<div class='methods col-4'>
<h3>Methods</h3>
<ul>
<li>
<a href="#__construct">__construct()</a>
</li>
<li>
<a href="#_appendFootnotes_callback">_appendFootnotes_callback()</a>
</li>
<li>
<a href="#_doAbbreviations_callback">_doAbbreviations_callback()</a>
</li>
<li>
<a href="#_doDefLists_callback">_doDefLists_callback()</a>
</li>
<li>
<a href="#_doFencedCodeBlocks_callback">_doFencedCodeBlocks_callback()</a>
</li>
<li>
<a href="#_doFencedCodeBlocks_newlines">_doFencedCodeBlocks_newlines()</a>
</li>
<li>
<a href="#_doHeaders_attr">_doHeaders_attr()</a>
</li>
<li>
<a href="#_doHeaders_callback_atx">_doHeaders_callback_atx()</a>
</li>
<li>
<a href="#_doHeaders_callback_setext">_doHeaders_callback_setext()</a>
</li>
<li>
<a href="#_doTable_callback">_doTable_callback()</a>
</li>
<li>
<a href="#_doTable_leadingPipe_callback">_doTable_leadingPipe_callback()</a>
</li>
<li>
<a href="#_hashHTMLBlocks_inHTML">_hashHTMLBlocks_inHTML()</a>
</li>
<li>
<a href="#_hashHTMLBlocks_inMarkdown">_hashHTMLBlocks_inMarkdown()</a>
</li>
<li>
<a href="#_processDefListItems_callback_dd">_processDefListItems_callback_dd()</a>
</li>
<li>
<a href="#_processDefListItems_callback_dt">_processDefListItems_callback_dt()</a>
</li>
<li>
<a href="#_stripAbbreviations_callback">_stripAbbreviations_callback()</a>
</li>
<li>
<a href="#_stripFootnotes_callback">_stripFootnotes_callback()</a>
</li>
<li>
<a href="#appendFootnotes">appendFootnotes()</a>
</li>
<li>
<a href="#doAbbreviations">doAbbreviations()</a>
</li>
<li>
<a href="#doDefLists">doDefLists()</a>
</li>
<li>
<a href="#doFencedCodeBlocks">doFencedCodeBlocks()</a>
</li>
<li>
<a href="#doFootnotes">doFootnotes()</a>
</li>
<li>
<a href="#doHeaders">doHeaders()</a>
</li>
<li>
<a href="#doTables">doTables()</a>
</li>
<li>
<a href="#formParagraphs">formParagraphs()</a>
</li>
<li>
<a href="#hashClean">hashClean()</a>
</li>
<li>
<a href="#hashHTMLBlocks">hashHTMLBlocks()</a>
</li>
<li>
<a href="#processDefListItems">processDefListItems()</a>
</li>
<li>
<a href="#setup">setup()</a>
</li>
<li>
<a href="#stripAbbreviations">stripAbbreviations()</a>
</li>
<li>
<a href="#stripFootnotes">stripFootnotes()</a>
</li>
<li>
<a href="#teardown">teardown()</a>
</li>
<li>
<a href="#_detab_callback">_detab_callback()</a>
</li>
<li>
<a href="#_doAnchors_inline_callback">_doAnchors_inline_callback()</a>
</li>
<li>
<a href="#_doAnchors_reference_callback">_doAnchors_reference_callback()</a>
</li>
<li>
<a href="#_doAutoLinks_email_callback">_doAutoLinks_email_callback()</a>
</li>
<li>
<a href="#_doAutoLinks_url_callback">_doAutoLinks_url_callback()</a>
</li>
<li>
<a href="#_doBlockQuotes_callback">_doBlockQuotes_callback()</a>
</li>
<li>
<a href="#_doBlockQuotes_callback2">_doBlockQuotes_callback2()</a>
</li>
<li>
<a href="#_doCodeBlocks_callback">_doCodeBlocks_callback()</a>
</li>
<li>
<a href="#_doHardBreaks_callback">_doHardBreaks_callback()</a>
</li>
<li>
<a href="#_doImages_inline_callback">_doImages_inline_callback()</a>
</li>
<li>
<a href="#_doImages_reference_callback">_doImages_reference_callback()</a>
</li>
<li>
<a href="#_doLists_callback">_doLists_callback()</a>
</li>
<li>
<a href="#_hashHTMLBlocks_callback">_hashHTMLBlocks_callback()</a>
</li>
<li>
<a href="#_initDetab">_initDetab()</a>
</li>
<li>
<a href="#_processListItems_callback">_processListItems_callback()</a>
</li>
<li>
<a href="#_stripLinkDefinitions_callback">_stripLinkDefinitions_callback()</a>
</li>
<li>
<a href="#_unhash_callback">_unhash_callback()</a>
</li>
<li>
<a href="#detab">detab()</a>
</li>
<li>
<a href="#doAnchors">doAnchors()</a>
</li>
<li>
<a href="#doAutoLinks">doAutoLinks()</a>
</li>
<li>
<a href="#doBlockQuotes">doBlockQuotes()</a>
</li>
<li>
<a href="#doCodeBlocks">doCodeBlocks()</a>
</li>
<li>
<a href="#doHardBreaks">doHardBreaks()</a>
</li>
<li>
<a href="#doHorizontalRules">doHorizontalRules()</a>
</li>
<li>
<a href="#doImages">doImages()</a>
</li>
<li>
<a href="#doItalicsAndBold">doItalicsAndBold()</a>
</li>
<li>
<a href="#doLists">doLists()</a>
</li>
<li>
<a href="#encodeAmpsAndAngles">encodeAmpsAndAngles()</a>
</li>
<li>
<a href="#encodeAttribute">encodeAttribute()</a>
</li>
<li>
<a href="#encodeEmailAddress">encodeEmailAddress()</a>
</li>
<li>
<a href="#handleSpanToken">handleSpanToken()</a>
</li>
<li>
<a href="#hashBlock">hashBlock()</a>
</li>
<li>
<a href="#hashPart">hashPart()</a>
</li>
<li>
<a href="#makeCodeSpan">makeCodeSpan()</a>
</li>
<li>
<a href="#outdent">outdent()</a>
</li>
<li>
<a href="#parseSpan">parseSpan()</a>
</li>
<li>
<a href="#prepareItalicsAndBold">prepareItalicsAndBold()</a>
</li>
<li>
<a href="#processListItems">processListItems()</a>
</li>
<li>
<a href="#runBasicBlockGamut">runBasicBlockGamut()</a>
</li>
<li>
<a href="#runBlockGamut">runBlockGamut()</a>
</li>
<li>
<a href="#runSpanGamut">runSpanGamut()</a>
</li>
<li>
<a href="#stripLinkDefinitions">stripLinkDefinitions()</a>
</li>
<li>
<a href="#transform">transform()</a>
</li>
<li>
<a href="#unhash">unhash()</a>
</li>

</ul>
</div>
</div>
<h1 id='properties'>Properties</h1>
<div class='properties'>
<dl>
<dt>
<h4 id='property-abbr_desciptions'><small>public</small>  <span class='blue'></span> $abbr_desciptions</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-abbr_word_re'><small>public</small>  <span class='blue'></span> $abbr_word_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(0)</span> ""</pre></dd>
<dt>
<h4 id='property-auto_close_tags_re'><small>public</small>  <span class='blue'></span> $auto_close_tags_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(6)</span> "hr|img"</pre></dd>
<dt>
<h4 id='property-block_gamut'><small>public</small>  <span class='blue'></span> $block_gamut</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(5)</span> <span>(
    "doHeaders" => <small>integer</small> 10
    "doHorizontalRules" => <small>integer</small> 20
    "doLists" => <small>integer</small> 40
    "doCodeBlocks" => <small>integer</small> 50
    "doBlockQuotes" => <small>integer</small> 60
)</span></pre></dd>
<dt>
<h4 id='property-block_tags_re'><small>public</small>  <span class='blue'></span> $block_tags_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(81)</span> "p|div|h[1-6]|blockquote|pre|table|dl|ol|ul|address|form|fieldset|iframe|hr|legend"</pre></dd>
<dt>
<h4 id='property-clean_tags_re'><small>public</small>  <span class='blue'></span> $clean_tags_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(11)</span> "script|math"</pre></dd>
<dt>
<h4 id='property-contain_span_tags_re'><small>public</small>  <span class='blue'></span> $contain_span_tags_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(38)</span> "p|h[1-6]|li|dd|dt|td|th|legend|address"</pre></dd>
<dt>
<h4 id='property-context_block_tags_re'><small>public</small>  <span class='blue'></span> $context_block_tags_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(28)</span> "script|noscript|math|ins|del"</pre></dd>
<dt>
<h4 id='property-document_gamut'><small>public</small>  <span class='blue'></span> $document_gamut</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(2)</span> <span>(
    "stripLinkDefinitions" => <small>integer</small> 20
    "runBasicBlockGamut" => <small>integer</small> 30
)</span></pre></dd>
<dt>
<h4 id='property-em_relist'><small>public</small>  <span class='blue'></span> $em_relist</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(3)</span> <span>(
    "" => <small>string</small><span>(61)</span> "(?:(?&lt;!\*)\*(?!\*)|(?&lt;![a-zA-Z0-9_])_(?!_))(?=\S)(?![.,:;]\s)"
    "*" => <small>string</small><span>(22)</span> "(?&lt;=\S)(?&lt;!\*)\*(?!\*)"
    "_" => <small>string</small><span>(30)</span> "(?&lt;=\S)(?&lt;!_)_(?![a-zA-Z0-9_])"
)</span></pre></dd>
<dt>
<h4 id='property-em_strong_prepared_relist'><small>public</small>  <span class='blue'></span> $em_strong_prepared_relist</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-em_strong_relist'><small>public</small>  <span class='blue'></span> $em_strong_relist</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(3)</span> <span>(
    "" => <small>string</small><span>(67)</span> "(?:(?&lt;!\*)\*\*\*(?!\*)|(?&lt;![a-zA-Z0-9_])___(?!_))(?=\S)(?![.,:;]\s)"
    "***" => <small>string</small><span>(26)</span> "(?&lt;=\S)(?&lt;!\*)\*\*\*(?!\*)"
    "___" => <small>string</small><span>(32)</span> "(?&lt;=\S)(?&lt;!_)___(?![a-zA-Z0-9_])"
)</span></pre></dd>
<dt>
<h4 id='property-empty_element_suffix'><small>public</small>  <span class='blue'></span> $empty_element_suffix</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(3)</span> " /&gt;"</pre></dd>
<dt>
<h4 id='property-escape_chars'><small>public</small>  <span class='blue'></span> $escape_chars</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(16)</span> "\`*_{}[]()&gt;#+-.!"</pre></dd>
<dt>
<h4 id='property-escape_chars_re'><small>public</small>  <span class='blue'></span> $escape_chars_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-fn_backlink_class'><small>public</small>  <span class='blue'></span> $fn_backlink_class</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(0)</span> ""</pre></dd>
<dt>
<h4 id='property-fn_backlink_title'><small>public</small>  <span class='blue'></span> $fn_backlink_title</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(0)</span> ""</pre></dd>
<dt>
<h4 id='property-fn_id_prefix'><small>public</small>  <span class='blue'></span> $fn_id_prefix</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(0)</span> ""</pre></dd>
<dt>
<h4 id='property-fn_link_class'><small>public</small>  <span class='blue'></span> $fn_link_class</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(0)</span> ""</pre></dd>
<dt>
<h4 id='property-fn_link_title'><small>public</small>  <span class='blue'></span> $fn_link_title</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(0)</span> ""</pre></dd>
<dt>
<h4 id='property-footnote_counter'><small>public</small>  <span class='blue'></span> $footnote_counter</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>integer</small> 1</pre></dd>
<dt>
<h4 id='property-footnotes'><small>public</small>  <span class='blue'></span> $footnotes</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-footnotes_ordered'><small>public</small>  <span class='blue'></span> $footnotes_ordered</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-html_hashes'><small>public</small>  <span class='blue'></span> $html_hashes</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-in_anchor'><small>public</small>  <span class='blue'></span> $in_anchor</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>bool</small> FALSE</pre></dd>
<dt>
<h4 id='property-list_level'><small>public</small>  <span class='blue'></span> $list_level</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>integer</small> 0</pre></dd>
<dt>
<h4 id='property-nested_brackets_depth'><small>public</small>  <span class='blue'></span> $nested_brackets_depth</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>integer</small> 6</pre></dd>
<dt>
<h4 id='property-nested_brackets_re'><small>public</small>  <span class='blue'></span> $nested_brackets_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-nested_url_parenthesis_depth'><small>public</small>  <span class='blue'></span> $nested_url_parenthesis_depth</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>integer</small> 4</pre></dd>
<dt>
<h4 id='property-nested_url_parenthesis_re'><small>public</small>  <span class='blue'></span> $nested_url_parenthesis_re</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>NULL</small></pre></dd>
<dt>
<h4 id='property-no_entities'><small>public</small>  <span class='blue'></span> $no_entities</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>bool</small> FALSE</pre></dd>
<dt>
<h4 id='property-no_markup'><small>public</small>  <span class='blue'></span> $no_markup</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>bool</small> FALSE</pre></dd>
<dt>
<h4 id='property-predef_abbr'><small>public</small>  <span class='blue'></span> $predef_abbr</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-predef_titles'><small>public</small>  <span class='blue'></span> $predef_titles</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-predef_urls'><small>public</small>  <span class='blue'></span> $predef_urls</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-span_gamut'><small>public</small>  <span class='blue'></span> $span_gamut</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(7)</span> <span>(
    "parseSpan" => <small>integer</small> -30
    "doImages" => <small>integer</small> 10
    "doAnchors" => <small>integer</small> 20
    "doAutoLinks" => <small>integer</small> 30
    "encodeAmpsAndAngles" => <small>integer</small> 40
    "doItalicsAndBold" => <small>integer</small> 50
    "doHardBreaks" => <small>integer</small> 60
)</span></pre></dd>
<dt>
<h4 id='property-strong_relist'><small>public</small>  <span class='blue'></span> $strong_relist</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(3)</span> <span>(
    "" => <small>string</small><span>(64)</span> "(?:(?&lt;!\*)\*\*(?!\*)|(?&lt;![a-zA-Z0-9_])__(?!_))(?=\S)(?![.,:;]\s)"
    "**" => <small>string</small><span>(24)</span> "(?&lt;=\S)(?&lt;!\*)\*\*(?!\*)"
    "__" => <small>string</small><span>(31)</span> "(?&lt;=\S)(?&lt;!_)__(?![a-zA-Z0-9_])"
)</span></pre></dd>
<dt>
<h4 id='property-tab_width'><small>public</small>  <span class='blue'></span> $tab_width</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>integer</small> 4</pre></dd>
<dt>
<h4 id='property-titles'><small>public</small>  <span class='blue'></span> $titles</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-urls'><small>public</small>  <span class='blue'></span> $urls</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>array</small><span>(0)</span> </pre></dd>
<dt>
<h4 id='property-utf8_strlen'><small>public</small>  <span class='blue'></span> $utf8_strlen</h4>
</dt>
<dd>
 </dd>
<dd>
 </dd>
<dd>
<small>Default value:</small>
<br />
 <pre class="debug"><small>string</small><span>(9)</span> "mb_strlen"</pre></dd>
</dl>
</div>
<h1 id='methods'>Methods</h1>
<div class='methods'>

<div class='method'>
<h3 id="__construct"><small>public</small>  __construct()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function __construct() {
#
# Constructor function. Initialize the parser object.
#
	# Add extra escapable characters before parent constructor 
	# initialize the table.
	$this-&gt;escape_chars .= &#039;:|&#039;;
	
	# Insert extra document, block, and span transformations. 
	# Parent constructor will do the sorting.
	$this-&gt;document_gamut += [
		&quot;doFencedCodeBlocks&quot; =&gt; 5,
		&quot;stripFootnotes&quot;     =&gt; 15,
		&quot;stripAbbreviations&quot; =&gt; 25,
		&quot;appendFootnotes&quot;    =&gt; 50,
		];
	$this-&gt;block_gamut += [
		&quot;doFencedCodeBlocks&quot; =&gt; 5,
		&quot;doTables&quot;           =&gt; 15,
		&quot;doDefLists&quot;         =&gt; 45,
		];
	$this-&gt;span_gamut += [
		&quot;doFootnotes&quot;        =&gt; 5,
		&quot;doAbbreviations&quot;    =&gt; 70,
		];
	
	parent::__construct();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_appendFootnotes_callback"><small>public</small>  _appendFootnotes_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _appendFootnotes_callback($matches) {
	$node_id = $this-&gt;fn_id_prefix . $matches[1];
	
	# Create footnote marker only if it has a corresponding footnote *and*
	# the footnote hasn&#039;t been used by another marker.
	if (isset($this-&gt;footnotes[$node_id])) {
		# Transfert footnote content to the ordered list.
		$this-&gt;footnotes_ordered[$node_id] = $this-&gt;footnotes[$node_id];
		unset($this-&gt;footnotes[$node_id]);
		
		$num = $this-&gt;footnote_counter++;
		$attr = &quot; rel=\&quot;footnote\&quot;&quot;;
		if ($this-&gt;fn_link_class != &quot;&quot;) {
			$class = $this-&gt;fn_link_class;
			$class = $this-&gt;encodeAttribute($class);
			$attr .= &quot; class=\&quot;$class\&quot;&quot;;
		}
		if ($this-&gt;fn_link_title != &quot;&quot;) {
			$title = $this-&gt;fn_link_title;
			$title = $this-&gt;encodeAttribute($title);
			$attr .= &quot; title=\&quot;$title\&quot;&quot;;
		}
		
		$attr = str_replace(&quot;%%&quot;, $num, $attr);
		$node_id = $this-&gt;encodeAttribute($node_id);
		
		return
			&quot;&lt;sup id=\&quot;fnref:$node_id\&quot;&gt;&quot;.
			&quot;&lt;a href=\&quot;#fn:$node_id\&quot;$attr&gt;$num&lt;/a&gt;&quot;.
			&quot;&lt;/sup&gt;&quot;;
	}
	
	return &quot;[^&quot;.$matches[1].&quot;]&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doAbbreviations_callback"><small>public</small>  _doAbbreviations_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doAbbreviations_callback($matches) {
	$abbr = $matches[0];
	if (isset($this-&gt;abbr_desciptions[$abbr])) {
		$desc = $this-&gt;abbr_desciptions[$abbr];
		if (empty($desc)) {
			return $this-&gt;hashPart(&quot;&lt;abbr&gt;$abbr&lt;/abbr&gt;&quot;);
		} else {
			$desc = $this-&gt;encodeAttribute($desc);
			return $this-&gt;hashPart(&quot;&lt;abbr title=\&quot;$desc\&quot;&gt;$abbr&lt;/abbr&gt;&quot;);
		}
	} else {
		return $matches[0];
	}
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doDefLists_callback"><small>public</small>  _doDefLists_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doDefLists_callback($matches) {
	# Re-usable patterns to match list item bullets and number markers:
	$list = $matches[1];
	
	# Turn double returns into triple returns, so that we can make a
	# paragraph for the last item in a list, if necessary:
	$result = trim($this-&gt;processDefListItems($list));
	$result = &quot;&lt;dl&gt;\n&quot; . $result . &quot;\n&lt;/dl&gt;&quot;;
	return $this-&gt;hashBlock($result) . &quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doFencedCodeBlocks_callback"><small>public</small>  _doFencedCodeBlocks_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doFencedCodeBlocks_callback($matches) {
	$codeblock = $matches[2];
	$codeblock = htmlspecialchars($codeblock, ENT_NOQUOTES);
	$codeblock = preg_replace_callback(&#039;/^\n+/&#039;,
		[&amp;$this, &#039;_doFencedCodeBlocks_newlines&#039;], $codeblock);
	$codeblock = &quot;&lt;pre&gt;&lt;code&gt;$codeblock&lt;/code&gt;&lt;/pre&gt;&quot;;
	return &quot;\n\n&quot;.$this-&gt;hashBlock($codeblock).&quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doFencedCodeBlocks_newlines"><small>public</small>  _doFencedCodeBlocks_newlines()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doFencedCodeBlocks_newlines($matches) {
	return str_repeat(&quot;&lt;br$this-&gt;empty_element_suffix&quot;, 
		strlen($matches[0]));
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doHeaders_attr"><small>public</small>  _doHeaders_attr()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doHeaders_attr($attr) {
	if (empty($attr))  return &quot;&quot;;
	return &quot; id=\&quot;$attr\&quot;&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doHeaders_callback_atx"><small>public</small>  _doHeaders_callback_atx()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doHeaders_callback_atx($matches) {
	$level = strlen($matches[1]);
	$attr  = $this-&gt;_doHeaders_attr($id =&amp; $matches[3]);
	$block = &quot;&lt;h$level$attr&gt;&quot;.$this-&gt;runSpanGamut($matches[2]).&quot;&lt;/h$level&gt;&quot;;
	return &quot;\n&quot; . $this-&gt;hashBlock($block) . &quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doHeaders_callback_setext"><small>public</small>  _doHeaders_callback_setext()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doHeaders_callback_setext($matches) {
	if ($matches[3] == &#039;-&#039; &amp;&amp; preg_match(&#039;{^- }&#039;, $matches[1]))
		return $matches[0];
	$level = $matches[3]{0} == &#039;=&#039; ? 1 : 2;
	$attr  = $this-&gt;_doHeaders_attr($id =&amp; $matches[2]);
	$block = &quot;&lt;h$level$attr&gt;&quot;.$this-&gt;runSpanGamut($matches[1]).&quot;&lt;/h$level&gt;&quot;;
	return &quot;\n&quot; . $this-&gt;hashBlock($block) . &quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doTable_callback"><small>public</small>  _doTable_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doTable_callback($matches) {
	$head		= $matches[1];
	$underline	= $matches[2];
	$content	= $matches[3];

	# Remove any tailing pipes for each line.
	$head		= preg_replace(&#039;/[|] *$/m&#039;, &#039;&#039;, $head);
	$underline	= preg_replace(&#039;/[|] *$/m&#039;, &#039;&#039;, $underline);
	$content	= preg_replace(&#039;/[|] *$/m&#039;, &#039;&#039;, $content);
	
	# Reading alignement from header underline.
	$separators	= preg_split(&#039;/ *[|] */&#039;, $underline);
	foreach ($separators as $n =&gt; $s) {
		if (preg_match(&#039;/^ *-+: *$/&#039;, $s))		$attr[$n] = &#039; align=&quot;right&quot;&#039;;
		else if (preg_match(&#039;/^ *:-+: *$/&#039;, $s))$attr[$n] = &#039; align=&quot;center&quot;&#039;;
		else if (preg_match(&#039;/^ *:-+ *$/&#039;, $s))	$attr[$n] = &#039; align=&quot;left&quot;&#039;;
		else									$attr[$n] = &#039;&#039;;
	}
	
	# Parsing span elements, including code spans, character escapes, 
	# and inline HTML tags, so that pipes inside those gets ignored.
	$head		= $this-&gt;parseSpan($head);
	$headers	= preg_split(&#039;/ *[|] */&#039;, $head);
	$col_count	= count($headers);
	
	# Write column headers.
	$text = &quot;&lt;table&gt;\n&quot;;
	$text .= &quot;&lt;thead&gt;\n&quot;;
	$text .= &quot;&lt;tr&gt;\n&quot;;
	foreach ($headers as $n =&gt; $header)
		$text .= &quot;  &lt;th$attr[$n]&gt;&quot;.$this-&gt;runSpanGamut(trim($header)).&quot;&lt;/th&gt;\n&quot;;
	$text .= &quot;&lt;/tr&gt;\n&quot;;
	$text .= &quot;&lt;/thead&gt;\n&quot;;
	
	# Split content by row.
	$rows = explode(&quot;\n&quot;, trim($content, &quot;\n&quot;));
	
	$text .= &quot;&lt;tbody&gt;\n&quot;;
	foreach ($rows as $row) {
		# Parsing span elements, including code spans, character escapes, 
		# and inline HTML tags, so that pipes inside those gets ignored.
		$row = $this-&gt;parseSpan($row);
		
		# Split row by cell.
		$row_cells = preg_split(&#039;/ *[|] */&#039;, $row, $col_count);
		$row_cells = array_pad($row_cells, $col_count, &#039;&#039;);
		
		$text .= &quot;&lt;tr&gt;\n&quot;;
		foreach ($row_cells as $n =&gt; $cell)
			$text .= &quot;  &lt;td$attr[$n]&gt;&quot;.$this-&gt;runSpanGamut(trim($cell)).&quot;&lt;/td&gt;\n&quot;;
		$text .= &quot;&lt;/tr&gt;\n&quot;;
	}
	$text .= &quot;&lt;/tbody&gt;\n&quot;;
	$text .= &quot;&lt;/table&gt;&quot;;
	
	return $this-&gt;hashBlock($text) . &quot;\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doTable_leadingPipe_callback"><small>public</small>  _doTable_leadingPipe_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doTable_leadingPipe_callback($matches) {
	$head		= $matches[1];
	$underline	= $matches[2];
	$content	= $matches[3];
	
	# Remove leading pipe for each row.
	$content	= preg_replace(&#039;/^ *[|]/m&#039;, &#039;&#039;, $content);
	
	return $this-&gt;_doTable_callback([$matches[0], $head, $underline, $content]);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_hashHTMLBlocks_inHTML"><small>public</small>  _hashHTMLBlocks_inHTML()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _hashHTMLBlocks_inHTML($text, $hash_method, $md_attr) {
#
# Parse HTML, calling _HashHTMLBlocks_InMarkdown for block tags.
#
# *   Calls $hash_method to convert any blocks.
# *   Stops when the first opening tag closes.
# *   $md_attr indicate if the use of the `markdown=&quot;1&quot;` attribute is allowed.
#     (it is not inside clean tags)
#
# Returns an array of that form: ( processed text , remaining text )
#
	if ($text === &#039;&#039;) return [&#039;&#039;, &#039;&#039;];
	
	# Regex to match `markdown` attribute inside of a tag.
	$markdown_attr_re = &#039;
		{
			\s*			# Eat whitespace before the `markdown` attribute
			markdown
			\s*=\s*
			(?&gt;
				([&quot;\&#039;])		# $1: quote delimiter		
				(.*?)		# $2: attribute value
				\1			# matching delimiter	
			|
				([^\s&gt;]*)	# $3: unquoted attribute value
			)
			()				# $4: make $3 always defined (avoid warnings)
		}xs&#039;;
	
	# Regex to match any tag.
	$tag_re = &#039;{
			(					# $2: Capture hole tag.
				&lt;/?					# Any opening or closing tag.
					[\w:$]+			# Tag name.
					(?:
						(?=[\s&quot;\&#039;/a-zA-Z0-9])	# Allowed characters after tag name.
						(?&gt;
							&quot;.*?&quot;		|	# Double quotes (can contain `&gt;`)
							\&#039;.*?\&#039;   	|	# Single quotes (can contain `&gt;`)
							.+?				# Anything but quotes and `&gt;`.
						)*?
					)?
				&gt;					# End of tag.
			|
				&lt;!--    .*?     --&gt;	# HTML Comment
			|
				&lt;\?.*?\?&gt; | &lt;%.*?%&gt;	# Processing instruction
			|
				&lt;!\[CDATA\[.*?\]\]&gt;	# CData Block
			)
		}xs&#039;;
	
	$original_text = $text;		# Save original text in case of faliure.
	
	$depth		= 0;	# Current depth inside the tag tree.
	$block_text	= &quot;&quot;;	# Temporary text holder for current text.
	$parsed		= &quot;&quot;;	# Parsed text that will be returned.

	#
	# Get the name of the starting tag.
	# (This pattern makes $base_tag_name_re safe without quoting.)
	#
	if (preg_match(&#039;/^&lt;([\w:$]*)\b/&#039;, $text, $matches))
		$base_tag_name_re = $matches[1];

	#
	# Loop through every tag until we find the corresponding closing tag.
	#
	do {
		#
		# Split the text using the first $tag_match pattern found.
		# Text before  pattern will be first in the array, text after
		# pattern will be at the end, and between will be any catches made 
		# by the pattern.
		#
		$parts = preg_split($tag_re, $text, 2, PREG_SPLIT_DELIM_CAPTURE);
		
		if (count($parts) &lt; 3) {
			#
			# End of $text reached with unbalenced tag(s).
			# In that case, we return original text unchanged and pass the
			# first character as filtered to prevent an infinite loop in the 
			# parent function.
			#
			return [$original_text{0}, substr($original_text, 1)];
		}
		
		$block_text .= $parts[0]; # Text before current tag.
		$tag         = $parts[1]; # Tag to handle.
		$text        = $parts[2]; # Remaining text after current tag.
		
		#
		# Check for: Auto-close tag (like &lt;hr/&gt;)
		#			 Comments and Processing Instructions.
		#
		if (preg_match(&#039;{^&lt;/?(?:&#039;.$this-&gt;auto_close_tags_re.&#039;)\b}&#039;, $tag) ||
			$tag{1} == &#039;!&#039; || $tag{1} == &#039;?&#039;)
		{
			# Just add the tag to the block as if it was text.
			$block_text .= $tag;
		}
		else {
			#
			# Increase/decrease nested tag count. Only do so if
			# the tag&#039;s name match base tag&#039;s.
			#
			if (preg_match(&#039;{^&lt;/?&#039;.$base_tag_name_re.&#039;\b}&#039;, $tag)) {
				if ($tag{1} == &#039;/&#039;)						$depth--;
				else if ($tag{strlen($tag)-2} != &#039;/&#039;)	$depth++;
			}
			
			#
			# Check for `markdown=&quot;1&quot;` attribute and handle it.
			#
			if ($md_attr &amp;&amp; 
				preg_match($markdown_attr_re, $tag, $attr_m) &amp;&amp;
				preg_match(&#039;/^1|block|span$/&#039;, $attr_m[2] . $attr_m[3]))
			{
				# Remove `markdown` attribute from opening tag.
				$tag = preg_replace($markdown_attr_re, &#039;&#039;, $tag);
				
				# Check if text inside this tag must be parsed in span mode.
				$this-&gt;mode = $attr_m[2] . $attr_m[3];
				$span_mode = $this-&gt;mode == &#039;span&#039; || $this-&gt;mode != &#039;block&#039; &amp;&amp;
					preg_match(&#039;{^&lt;(?:&#039;.$this-&gt;contain_span_tags_re.&#039;)\b}&#039;, $tag);
				
				# Calculate indent before tag.
				if (preg_match(&#039;/(?:^|\n)( *?)(?! ).*?$/&#039;, $block_text, $matches)) {
					$strlen = $this-&gt;utf8_strlen;
					$indent = $strlen($matches[1], &#039;UTF-8&#039;);
				} else {
					$indent = 0;
				}
				
				# End preceding block with this tag.
				$block_text .= $tag;
				$parsed .= $this-&gt;$hash_method($block_text);
				
				# Get enclosing tag name for the ParseMarkdown function.
				# (This pattern makes $tag_name_re safe without quoting.)
				preg_match(&#039;/^&lt;([\w:$]*)\b/&#039;, $tag, $matches);
				$tag_name_re = $matches[1];
				
				# Parse the content using the HTML-in-Markdown parser.
				list ($block_text, $text)
					= $this-&gt;_hashHTMLBlocks_inMarkdown($text, $indent, 
						$tag_name_re, $span_mode);
				
				# Outdent markdown text.
				if ($indent &gt; 0) {
					$block_text = preg_replace(&quot;/^[ ]{1,$indent}/m&quot;, &quot;&quot;, 
												$block_text);
				}
				
				# Append tag content to parsed text.
				if (!$span_mode)	$parsed .= &quot;\n\n$block_text\n\n&quot;;
				else				$parsed .= &quot;$block_text&quot;;
				
				# Start over a new block.
				$block_text = &quot;&quot;;
			}
			else $block_text .= $tag;
		}
		
	} while ($depth &gt; 0);
	
	#
	# Hash last block text that wasn&#039;t processed inside the loop.
	#
	$parsed .= $this-&gt;$hash_method($block_text);
	
	return [$parsed, $text];
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_hashHTMLBlocks_inMarkdown"><small>public</small>  _hashHTMLBlocks_inMarkdown()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _hashHTMLBlocks_inMarkdown($text, $indent = 0, 
									$enclosing_tag_re = &#039;&#039;, $span = false)
{
#
# Parse markdown text, calling _HashHTMLBlocks_InHTML for block tags.
#
# *   $indent is the number of space to be ignored when checking for code 
#     blocks. This is important because if we don&#039;t take the indent into 
#     account, something like this (which looks right) won&#039;t work as expected:
#
#     &lt;div&gt;
#         &lt;div markdown=&quot;1&quot;&gt;
#         Hello World.  &lt;-- Is this a Markdown code block or text?
#         &lt;/div&gt;  &lt;-- Is this a Markdown code block or a real tag?
#     &lt;div&gt;
#
#     If you don&#039;t like this, just don&#039;t indent the tag on which
#     you apply the markdown=&quot;1&quot; attribute.
#
# *   If $enclosing_tag_re is not empty, stops at the first unmatched closing 
#     tag with that name. Nested tags supported.
#
# *   If $span is true, text inside must treated as span. So any double 
#     newline will be replaced by a single newline so that it does not create 
#     paragraphs.
#
# Returns an array of that form: ( processed text , remaining text )
#
	if ($text === &#039;&#039;) return [&#039;&#039;, &#039;&#039;];

	# Regex to check for the presense of newlines around a block tag.
	$newline_before_re = &#039;/(?:^\n?|\n\n)*$/&#039;;
	$newline_after_re = 
		&#039;{
			^						# Start of text following the tag.
			(?&gt;[ ]*&lt;!--.*?--&gt;)?		# Optional comment.
			[ ]*\n					# Must be followed by newline.
		}xs&#039;;
	
	# Regex to match any tag.
	$block_tag_re =
		&#039;{
			(					# $2: Capture hole tag.
				&lt;/?					# Any opening or closing tag.
					(?&gt;				# Tag name.
						&#039;.$this-&gt;block_tags_re.&#039;			|
						&#039;.$this-&gt;context_block_tags_re.&#039;	|
						&#039;.$this-&gt;clean_tags_re.&#039;        	|
						(?!\s)&#039;.$enclosing_tag_re.&#039;
					)
					(?:
						(?=[\s&quot;\&#039;/a-zA-Z0-9])	# Allowed characters after tag name.
						(?&gt;
							&quot;.*?&quot;		|	# Double quotes (can contain `&gt;`)
							\&#039;.*?\&#039;   	|	# Single quotes (can contain `&gt;`)
							.+?				# Anything but quotes and `&gt;`.
						)*?
					)?
				&gt;					# End of tag.
			|
				&lt;!--    .*?     --&gt;	# HTML Comment
			|
				&lt;\?.*?\?&gt; | &lt;%.*?%&gt;	# Processing instruction
			|
				&lt;!\[CDATA\[.*?\]\]&gt;	# CData Block
			|
				# Code span marker
				`+
			&#039;. ( !$span ? &#039; # If not in span.
			|
				# Indented code block
				(?&gt; ^[ ]*\n? | \n[ ]*\n )
				[ ]{&#039;.($indent+4).&#039;}[^\n]* \n
				(?&gt;
					(?: [ ]{&#039;.($indent+4).&#039;}[^\n]* | [ ]* ) \n
				)*
			|
				# Fenced code block marker
				(?&gt; ^ | \n )
				[ ]{&#039;.($indent).&#039;}~~~+[ ]*\n
			&#039; : &#039;&#039; ). &#039; # End (if not is span).
			)
		}xs&#039;;

	
	$depth = 0;		# Current depth inside the tag tree.
	$parsed = &quot;&quot;;	# Parsed text that will be returned.

	#
	# Loop through every tag until we find the closing tag of the parent
	# or loop until reaching the end of text if no parent tag specified.
	#
	do {
		#
		# Split the text using the first $tag_match pattern found.
		# Text before  pattern will be first in the array, text after
		# pattern will be at the end, and between will be any catches made 
		# by the pattern.
		#
		$parts = preg_split($block_tag_re, $text, 2, 
							PREG_SPLIT_DELIM_CAPTURE);
		
		# If in Markdown span mode, add a empty-string span-level hash 
		# after each newline to prevent triggering any block element.
		if ($span) {
			$void = $this-&gt;hashPart(&quot;&quot;, &#039;:&#039;);
			$newline = &quot;$void\n&quot;;
			$parts[0] = $void . str_replace(&quot;\n&quot;, $newline, $parts[0]) . $void;
		}
		
		$parsed .= $parts[0]; # Text before current tag.
		
		# If end of $text has been reached. Stop loop.
		if (count($parts) &lt; 3) {
			$text = &quot;&quot;;
			break;
		}
		
		$tag  = $parts[1]; # Tag to handle.
		$text = $parts[2]; # Remaining text after current tag.
		$tag_re = preg_quote($tag); # For use in a regular expression.
		
		#
		# Check for: Code span marker
		#
		if ($tag{0} == &quot;`&quot;) {
			# Find corresponding end marker.
			$tag_re = preg_quote($tag);
			if (preg_match(&#039;{^(?&gt;.+?|\n(?!\n))*?(?&lt;!`)&#039;.$tag_re.&#039;(?!`)}&#039;,
				$text, $matches))
			{
				# End marker found: pass text unchanged until marker.
				$parsed .= $tag . $matches[0];
				$text = substr($text, strlen($matches[0]));
			}
			else {
				# Unmatched marker: just skip it.
				$parsed .= $tag;
			}
		}
		#
		# Check for: Indented code block or fenced code block marker.
		#
		else if ($tag{0} == &quot;\n&quot; || $tag{0} == &quot;~&quot;) {
			if ($tag{1} == &quot;\n&quot; || $tag{1} == &quot; &quot;) {
				# Indented code block: pass it unchanged, will be handled 
				# later.
				$parsed .= $tag;
			}
			else {
				# Fenced code block marker: find matching end marker.
				$tag_re = preg_quote(trim($tag));
				if (preg_match(&#039;{^(?&gt;.*\n)+?&#039;.$tag_re.&#039; *\n}&#039;, $text, 
					$matches)) 
				{
					# End marker found: pass text unchanged until marker.
					$parsed .= $tag . $matches[0];
					$text = substr($text, strlen($matches[0]));
				}
				else {
					# No end marker: just skip it.
					$parsed .= $tag;
				}
			}
		}
		#
		# Check for: Opening Block level tag or
		#            Opening Context Block tag (like ins and del) 
		#               used as a block tag (tag is alone on it&#039;s line).
		#
		else if (preg_match(&#039;{^&lt;(?:&#039;.$this-&gt;block_tags_re.&#039;)\b}&#039;, $tag) ||
			(	preg_match(&#039;{^&lt;(?:&#039;.$this-&gt;context_block_tags_re.&#039;)\b}&#039;, $tag) &amp;&amp;
				preg_match($newline_before_re, $parsed) &amp;&amp;
				preg_match($newline_after_re, $text)	)
			)
		{
			# Need to parse tag and following text using the HTML parser.
			list($block_text, $text) = 
				$this-&gt;_hashHTMLBlocks_inHTML($tag . $text, &quot;hashBlock&quot;, true);
			
			# Make sure it stays outside of any paragraph by adding newlines.
			$parsed .= &quot;\n\n$block_text\n\n&quot;;
		}
		#
		# Check for: Clean tag (like script, math)
		#            HTML Comments, processing instructions.
		#
		else if (preg_match(&#039;{^&lt;(?:&#039;.$this-&gt;clean_tags_re.&#039;)\b}&#039;, $tag) ||
			$tag{1} == &#039;!&#039; || $tag{1} == &#039;?&#039;)
		{
			# Need to parse tag and following text using the HTML parser.
			# (don&#039;t check for markdown attribute)
			list($block_text, $text) = 
				$this-&gt;_hashHTMLBlocks_inHTML($tag . $text, &quot;hashClean&quot;, false);
			
			$parsed .= $block_text;
		}
		#
		# Check for: Tag with same name as enclosing tag.
		#
		else if ($enclosing_tag_re !== &#039;&#039; &amp;&amp;
			# Same name as enclosing tag.
			preg_match(&#039;{^&lt;/?(?:&#039;.$enclosing_tag_re.&#039;)\b}&#039;, $tag))
		{
			#
			# Increase/decrease nested tag count.
			#
			if ($tag{1} == &#039;/&#039;)						$depth--;
			else if ($tag{strlen($tag)-2} != &#039;/&#039;)	$depth++;

			if ($depth &lt; 0) {
				#
				# Going out of parent element. Clean up and break so we
				# return to the calling function.
				#
				$text = $tag . $text;
				break;
			}
			
			$parsed .= $tag;
		}
		else {
			$parsed .= $tag;
		}
	} while ($depth &gt;= 0);
	
	return [$parsed, $text];
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_processDefListItems_callback_dd"><small>public</small>  _processDefListItems_callback_dd()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _processDefListItems_callback_dd($matches) {
	$leading_line	= $matches[1];
	$marker_space	= $matches[2];
	$def			= $matches[3];

	if ($leading_line || preg_match(&#039;/\n{2,}/&#039;, $def)) {
		# Replace marker with the appropriate whitespace indentation
		$def = str_repeat(&#039; &#039;, strlen($marker_space)) . $def;
		$def = $this-&gt;runBlockGamut($this-&gt;outdent($def . &quot;\n\n&quot;));
		$def = &quot;\n&quot;. $def .&quot;\n&quot;;
	}
	else {
		$def = rtrim($def);
		$def = $this-&gt;runSpanGamut($this-&gt;outdent($def));
	}

	return &quot;\n&lt;dd&gt;&quot; . $def . &quot;&lt;/dd&gt;\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_processDefListItems_callback_dt"><small>public</small>  _processDefListItems_callback_dt()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _processDefListItems_callback_dt($matches) {
	$terms = explode(&quot;\n&quot;, trim($matches[1]));
	$text = &#039;&#039;;
	foreach ($terms as $term) {
		$term = $this-&gt;runSpanGamut(trim($term));
		$text .= &quot;\n&lt;dt&gt;&quot; . $term . &quot;&lt;/dt&gt;&quot;;
	}
	return $text . &quot;\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_stripAbbreviations_callback"><small>public</small>  _stripAbbreviations_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _stripAbbreviations_callback($matches) {
	$abbr_word = $matches[1];
	$abbr_desc = $matches[2];
	if ($this-&gt;abbr_word_re)
		$this-&gt;abbr_word_re .= &#039;|&#039;;
	$this-&gt;abbr_word_re .= preg_quote($abbr_word);
	$this-&gt;abbr_desciptions[$abbr_word] = trim($abbr_desc);
	return &#039;&#039;; # String that will replace the block
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_stripFootnotes_callback"><small>public</small>  _stripFootnotes_callback()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _stripFootnotes_callback($matches) {
	$note_id = $this-&gt;fn_id_prefix . $matches[1];
	$this-&gt;footnotes[$note_id] = $this-&gt;outdent($matches[2]);
	return &#039;&#039;; # String that will replace the block
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="appendFootnotes"><small>public</small>  appendFootnotes()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function appendFootnotes($text) {
#
# Append footnote list to text.
#
	$text = preg_replace_callback(&#039;{F\x1Afn:(.*?)\x1A:}&#039;, 
		[&amp;$this, &#039;_appendFootnotes_callback&#039;], $text);

	if (!empty($this-&gt;footnotes_ordered)) {
		$text .= &quot;\n\n&quot;;
		$text .= &quot;&lt;div class=\&quot;footnotes\&quot;&gt;\n&quot;;
		$text .= &quot;&lt;hr&quot;. MARKDOWN_EMPTY_ELEMENT_SUFFIX .&quot;\n&quot;;
		$text .= &quot;&lt;ol&gt;\n\n&quot;;
		
		$attr = &quot; rev=\&quot;footnote\&quot;&quot;;
		if ($this-&gt;fn_backlink_class != &quot;&quot;) {
			$class = $this-&gt;fn_backlink_class;
			$class = $this-&gt;encodeAttribute($class);
			$attr .= &quot; class=\&quot;$class\&quot;&quot;;
		}
		if ($this-&gt;fn_backlink_title != &quot;&quot;) {
			$title = $this-&gt;fn_backlink_title;
			$title = $this-&gt;encodeAttribute($title);
			$attr .= &quot; title=\&quot;$title\&quot;&quot;;
		}
		$num = 0;
		
		while (!empty($this-&gt;footnotes_ordered)) {
			$footnote = reset($this-&gt;footnotes_ordered);
			$note_id = key($this-&gt;footnotes_ordered);
			unset($this-&gt;footnotes_ordered[$note_id]);
			
			$footnote .= &quot;\n&quot;; # Need to append newline before parsing.
			$footnote = $this-&gt;runBlockGamut(&quot;$footnote\n&quot;);				
			$footnote = preg_replace_callback(&#039;{F\x1Afn:(.*?)\x1A:}&#039;, 
				[&amp;$this, &#039;_appendFootnotes_callback&#039;], $footnote);
			
			$attr = str_replace(&quot;%%&quot;, ++$num, $attr);
			$note_id = $this-&gt;encodeAttribute($note_id);
			
			# Add backlink to last paragraph; create new paragraph if needed.
			$backlink = &quot;&lt;a href=\&quot;#fnref:$note_id\&quot;$attr&gt;&amp;#8617;&lt;/a&gt;&quot;;
			if (preg_match(&#039;{&lt;/p&gt;$}&#039;, $footnote)) {
				$footnote = substr($footnote, 0, -4) . &quot;&amp;#160;$backlink&lt;/p&gt;&quot;;
			} else {
				$footnote .= &quot;\n\n&lt;p&gt;$backlink&lt;/p&gt;&quot;;
			}
			
			$text .= &quot;&lt;li id=\&quot;fn:$note_id\&quot;&gt;\n&quot;;
			$text .= $footnote . &quot;\n&quot;;
			$text .= &quot;&lt;/li&gt;\n\n&quot;;
		}
		
		$text .= &quot;&lt;/ol&gt;\n&quot;;
		$text .= &quot;&lt;/div&gt;&quot;;
	}
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doAbbreviations"><small>public</small>  doAbbreviations()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doAbbreviations($text) {
#
# Find defined abbreviations in text and wrap them in &lt;abbr&gt; elements.
#
	if ($this-&gt;abbr_word_re) {
		// cannot use the /x modifier because abbr_word_re may 
		// contain significant spaces:
		$text = preg_replace_callback(&#039;{&#039;.
			&#039;(?&lt;![\w\x1A])&#039;.
			&#039;(?:&#039;.$this-&gt;abbr_word_re.&#039;)&#039;.
			&#039;(?![\w\x1A])&#039;.
			&#039;}&#039;, 
			[&amp;$this, &#039;_doAbbreviations_callback&#039;], $text);
	}
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doDefLists"><small>public</small>  doDefLists()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doDefLists($text) {
#
# Form HTML definition lists.
#
	$less_than_tab = $this-&gt;tab_width - 1;

	# Re-usable pattern to match any entire dl list:
	$whole_list_re = &#039;(?&gt;
		(								# $1 = whole list
		  (								# $2
			[ ]{0,&#039;.$less_than_tab.&#039;}
			((?&gt;.*\S.*\n)+)				# $3 = defined term
			\n?
			[ ]{0,&#039;.$less_than_tab.&#039;}:[ ]+ # colon starting definition
		  )
		  (?s:.+?)
		  (								# $4
			  \z
			|
			  \n{2,}
			  (?=\S)
			  (?!						# Negative lookahead for another term
				[ ]{0,&#039;.$less_than_tab.&#039;}
				(?: \S.*\n )+?			# defined term
				\n?
				[ ]{0,&#039;.$less_than_tab.&#039;}:[ ]+ # colon starting definition
			  )
			  (?!						# Negative lookahead for another definition
				[ ]{0,&#039;.$less_than_tab.&#039;}:[ ]+ # colon starting definition
			  )
		  )
		)
	)&#039;; // mx

	$text = preg_replace_callback(&#039;{
			(?&gt;\A\n?|(?&lt;=\n\n))
			&#039;.$whole_list_re.&#039;
		}mx&#039;,
		[&amp;$this, &#039;_doDefLists_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doFencedCodeBlocks"><small>public</small>  doFencedCodeBlocks()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doFencedCodeBlocks($text) {
#
# Adding the fenced code block syntax to regular Markdown:
#
# ~~~
# Code block
# ~~~
#
	$less_than_tab = $this-&gt;tab_width;
	
	$text = preg_replace_callback(&#039;{
			(?:\n|\A)
			# 1: Opening marker
			(
				~{3,} # Marker: three tilde or more.
			)
			[ ]* \n # Whitespace and newline following marker.
			
			# 2: Content
			(
				(?&gt;
					(?!\1 [ ]* \n)	# Not a closing marker.
					.*\n+
				)+
			)
			
			# Closing marker.
			\1 [ ]* \n
		}xm&#039;,
		[&amp;$this, &#039;_doFencedCodeBlocks_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doFootnotes"><small>public</small>  doFootnotes()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doFootnotes($text) {
#
# Replace footnote references in $text [^id] with a special text-token 
# which will be replaced by the actual footnote marker in appendFootnotes.
#
	if (!$this-&gt;in_anchor) {
		$text = preg_replace(&#039;{\[\^(.+?)\]}&#039;, &quot;F\x1Afn:\\1\x1A:&quot;, $text);
	}
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doHeaders"><small>public</small>  doHeaders()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doHeaders($text) {
#
# Redefined to add id attribute support.
#
	# Setext-style headers:
	#	  Header 1  {#header1}
	#	  ========
	#  
	#	  Header 2  {#header2}
	#	  --------
	#
	$text = preg_replace_callback(
		&#039;{
			(^.+?)								# $1: Header text
			(?:[ ]+\{\#([-_:a-zA-Z0-9]+)\})?	# $2: Id attribute
			[ ]*\n(=+|-+)[ ]*\n+				# $3: Header footer
		}mx&#039;,
		[&amp;$this, &#039;_doHeaders_callback_setext&#039;], $text);

	# atx-style headers:
	#	# Header 1        {#header1}
	#	## Header 2       {#header2}
	#	## Header 2 with closing hashes ##  {#header3}
	#	...
	#	###### Header 6   {#header2}
	#
	$text = preg_replace_callback(&#039;{
			^(\#{1,6})	# $1 = string of #\&#039;s
			[ ]*
			(.+?)		# $2 = Header text
			[ ]*
			\#*			# optional closing #\&#039;s (not counted)
			(?:[ ]+\{\#([-_:a-zA-Z0-9]+)\})? # id attribute
			[ ]*
			\n+
		}xm&#039;,
		[&amp;$this, &#039;_doHeaders_callback_atx&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doTables"><small>public</small>  doTables()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doTables($text) {
#
# Form HTML tables.
#
	$less_than_tab = $this-&gt;tab_width - 1;
	#
	# Find tables with leading pipe.
	#
	#	| Header 1 | Header 2
	#	| -------- | --------
	#	| Cell 1   | Cell 2
	#	| Cell 3   | Cell 4
	#
	$text = preg_replace_callback(&#039;
		{
			^							# Start of a line
			[ ]{0,&#039;.$less_than_tab.&#039;}	# Allowed whitespace.
			[|]							# Optional leading pipe (present)
			(.+) \n						# $1: Header row (at least one pipe)
			
			[ ]{0,&#039;.$less_than_tab.&#039;}	# Allowed whitespace.
			[|] ([ ]*[-:]+[-| :]*) \n	# $2: Header underline
			
			(							# $3: Cells
				(?&gt;
					[ ]*				# Allowed whitespace.
					[|] .* \n			# Row content.
				)*
			)
			(?=\n|\Z)					# Stop at final double newline.
		}xm&#039;,
		[&amp;$this, &#039;_doTable_leadingPipe_callback&#039;], $text);
	
	#
	# Find tables without leading pipe.
	#
	#	Header 1 | Header 2
	#	-------- | --------
	#	Cell 1   | Cell 2
	#	Cell 3   | Cell 4
	#
	$text = preg_replace_callback(&#039;
		{
			^							# Start of a line
			[ ]{0,&#039;.$less_than_tab.&#039;}	# Allowed whitespace.
			(\S.*[|].*) \n				# $1: Header row (at least one pipe)
			
			[ ]{0,&#039;.$less_than_tab.&#039;}	# Allowed whitespace.
			([-:]+[ ]*[|][-| :]*) \n	# $2: Header underline
			
			(							# $3: Cells
				(?&gt;
					.* [|] .* \n		# Row content
				)*
			)
			(?=\n|\Z)					# Stop at final double newline.
		}xm&#039;,
		[&amp;$this, &#039;_DoTable_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="formParagraphs"><small>public</small>  formParagraphs()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function formParagraphs($text) {
#
#	Params:
#		$text - string to process with html &lt;p&gt; tags
#
	# Strip leading and trailing lines:
	$text = preg_replace(&#039;/\A\n+|\n+\z/&#039;, &#039;&#039;, $text);
	
	$grafs = preg_split(&#039;/\n{2,}/&#039;, $text, -1, PREG_SPLIT_NO_EMPTY);

	#
	# Wrap &lt;p&gt; tags and unhashify HTML blocks
	#
	foreach ($grafs as $key =&gt; $value) {
		$value = trim($this-&gt;runSpanGamut($value));
		
		# Check if this should be enclosed in a paragraph.
		# Clean tag hashes &amp; block tag hashes are left alone.
		$is_p = !preg_match(&#039;/^B\x1A[0-9]+B|^C\x1A[0-9]+C$/&#039;, $value);
		
		if ($is_p) {
			$value = &quot;&lt;p&gt;$value&lt;/p&gt;&quot;;
		}
		$grafs[$key] = $value;
	}
	
	# Join grafs in one text, then unhash HTML tags. 
	$text = implode(&quot;\n\n&quot;, $grafs);
	
	# Finish by removing any tag hashes still present in $text.
	$text = $this-&gt;unhash($text);
	
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="hashClean"><small>public</small>  hashClean()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function hashClean($text) {
#
# Called whenever a tag must be hashed when a function insert a &quot;clean&quot; tag
# in $text, it pass through this function and is automaticaly escaped, 
# blocking invalid nested overlap.
#
	return $this-&gt;hashPart($text, &#039;C&#039;);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="hashHTMLBlocks"><small>public</small>  hashHTMLBlocks()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function hashHTMLBlocks($text) {
#
# Hashify HTML Blocks and &quot;clean tags&quot;.
#
# We only want to do this for block-level HTML tags, such as headers,
# lists, and tables. That&#039;s because we still want to wrap &lt;p&gt;s around
# &quot;paragraphs&quot; that are wrapped in non-block-level tags, such as anchors,
# phrase emphasis, and spans. The list of tags we&#039;re looking for is
# hard-coded.
#
# This works by calling _HashHTMLBlocks_InMarkdown, which then calls
# _HashHTMLBlocks_InHTML when it encounter block tags. When the markdown=&quot;1&quot; 
# attribute is found whitin a tag, _HashHTMLBlocks_InHTML calls back
#  _HashHTMLBlocks_InMarkdown to handle the Markdown syntax within the tag.
# These two functions are calling each other. It&#039;s recursive!
#
	#
	# Call the HTML-in-Markdown hasher.
	#
	list($text, ) = $this-&gt;_hashHTMLBlocks_inMarkdown($text);
	
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="processDefListItems"><small>public</small>  processDefListItems()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function processDefListItems($list_str) {
#
#	Process the contents of a single definition list, splitting it
#	into individual term and definition list items.
#
	$less_than_tab = $this-&gt;tab_width - 1;
	
	# trim trailing blank lines:
	$list_str = preg_replace(&quot;/\n{2,}\\z/&quot;, &quot;\n&quot;, $list_str);

	# Process definition terms.
	$list_str = preg_replace_callback(&#039;{
		(?&gt;\A\n?|\n\n+)					# leading line
		(								# definition terms = $1
			[ ]{0,&#039;.$less_than_tab.&#039;}	# leading whitespace
			(?![:][ ]|[ ])				# negative lookahead for a definition 
										#   mark (colon) or more whitespace.
			(?&gt; \S.* \n)+?				# actual term (not whitespace).	
		)			
		(?=\n?[ ]{0,3}:[ ])				# lookahead for following line feed 
										#   with a definition mark.
		}xm&#039;,
		[&amp;$this, &#039;_processDefListItems_callback_dt&#039;], $list_str);

	# Process actual definitions.
	$list_str = preg_replace_callback(&#039;{
		\n(\n+)?						# leading line = $1
		(								# marker space = $2
			[ ]{0,&#039;.$less_than_tab.&#039;}	# whitespace before colon
			[:][ ]+						# definition mark (colon)
		)
		((?s:.+?))						# definition text = $3
		(?= \n+ 						# stop at next definition mark,
			(?:							# next term or end of text
				[ ]{0,&#039;.$less_than_tab.&#039;} [:][ ]	|
				&lt;dt&gt; | \z
			)						
		)					
		}xm&#039;,
		[&amp;$this, &#039;_processDefListItems_callback_dd&#039;], $list_str);

	return $list_str;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="setup"><small>public</small>  setup()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function setup() {
#
# Setting up Extra-specific variables.
#
	parent::setup();
	
	$this-&gt;footnotes = [];
	$this-&gt;footnotes_ordered = [];
	$this-&gt;abbr_desciptions = [];
	$this-&gt;abbr_word_re = &#039;&#039;;
	$this-&gt;footnote_counter = 1;
	
	foreach ($this-&gt;predef_abbr as $abbr_word =&gt; $abbr_desc) {
		if ($this-&gt;abbr_word_re)
			$this-&gt;abbr_word_re .= &#039;|&#039;;
		$this-&gt;abbr_word_re .= preg_quote($abbr_word);
		$this-&gt;abbr_desciptions[$abbr_word] = trim($abbr_desc);
	}
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="stripAbbreviations"><small>public</small>  stripAbbreviations()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function stripAbbreviations($text) {
#
# Strips abbreviations from text, stores titles in hash references.
#
	$less_than_tab = $this-&gt;tab_width - 1;

	# Link defs are in the form: [id]*: url &quot;optional title&quot;
	$text = preg_replace_callback(&#039;{
		^[ ]{0,&#039;.$less_than_tab.&#039;}\*\[(.+?)\][ ]?:	# abbr_id = $1
		(.*)					# text = $2 (no blank lines allowed)	
		}xm&#039;,
		[&amp;$this, &#039;_stripAbbreviations_callback&#039;],
		$text);
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="stripFootnotes"><small>public</small>  stripFootnotes()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function stripFootnotes($text) {
#
# Strips link definitions from text, stores the URLs and titles in
# hash references.
#
	$less_than_tab = $this-&gt;tab_width - 1;

	# Link defs are in the form: [^id]: url &quot;optional title&quot;
	$text = preg_replace_callback(&#039;{
		^[ ]{0,&#039;.$less_than_tab.&#039;}\[\^(.+?)\][ ]?:	# note_id = $1
		  [ ]*
		  \n?					# maybe *one* newline
		(						# text = $2 (no blank lines allowed)
			(?:					
				.+				# actual text
			|
				\n				# newlines but 
				(?!\[\^.+?\]:\s)# negative lookahead for footnote marker.
				(?!\n+[ ]{0,3}\S)# ensure line is not blank and followed 
								# by non-indented content
			)*
		)		
		}xm&#039;,
		[&amp;$this, &#039;_stripFootnotes_callback&#039;],
		$text);
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="teardown"><small>public</small>  teardown()<small> (defined in <a href='/documentation/api/MarkdownExtra_Parser'>MarkdownExtra_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function teardown() {
#
# Clearing Extra-specific variables.
#
	$this-&gt;footnotes = [];
	$this-&gt;footnotes_ordered = [];
	$this-&gt;abbr_desciptions = [];
	$this-&gt;abbr_word_re = &#039;&#039;;
	
	parent::teardown();
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_detab_callback"><small>public</small>  _detab_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _detab_callback($matches) {
	$line = $matches[0];
	$strlen = $this-&gt;utf8_strlen; # strlen function for UTF-8.
	
	# Split in blocks.
	$blocks = explode(&quot;\t&quot;, $line);
	# Add each blocks to the line.
	$line = $blocks[0];
	unset($blocks[0]); # Do not add first block twice.
	foreach ($blocks as $block) {
		# Calculate amount of space, insert spaces, insert block.
		$amount = $this-&gt;tab_width - 
			$strlen($line, &#039;UTF-8&#039;) % $this-&gt;tab_width;
		$line .= str_repeat(&quot; &quot;, $amount) . $block;
	}
	return $line;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doAnchors_inline_callback"><small>public</small>  _doAnchors_inline_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doAnchors_inline_callback($matches) {
	$whole_match	=  $matches[1];
	$link_text		=  $this-&gt;runSpanGamut($matches[2]);
	$url			=  $matches[3] == &#039;&#039; ? $matches[4] : $matches[3];
	$title			=&amp; $matches[7];

	$url = $this-&gt;encodeAttribute($url);

	$result = &quot;&lt;a href=\&quot;$url\&quot;&quot;;
	if (isset($title)) {
		$title = $this-&gt;encodeAttribute($title);
		$result .=  &quot; title=\&quot;$title\&quot;&quot;;
	}
	
	$link_text = $this-&gt;runSpanGamut($link_text);
	$result .= &quot;&gt;$link_text&lt;/a&gt;&quot;;

	return $this-&gt;hashPart($result);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doAnchors_reference_callback"><small>public</small>  _doAnchors_reference_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doAnchors_reference_callback($matches) {
	$whole_match =  $matches[1];
	$link_text   =  $matches[2];
	$link_id     =&amp; $matches[3];

	if ($link_id == &quot;&quot;) {
		# for shortcut links like [this][] or [this].
		$link_id = $link_text;
	}
	
	# lower-case and turn embedded newlines into spaces
	$link_id = strtolower($link_id);
	$link_id = preg_replace(&#039;{[ ]?\n}&#039;, &#039; &#039;, $link_id);

	if (isset($this-&gt;urls[$link_id])) {
		$url = $this-&gt;urls[$link_id];
		$url = $this-&gt;encodeAttribute($url);
		
		$result = &quot;&lt;a href=\&quot;$url\&quot;&quot;;
		if ( isset( $this-&gt;titles[$link_id] ) ) {
			$title = $this-&gt;titles[$link_id];
			$title = $this-&gt;encodeAttribute($title);
			$result .=  &quot; title=\&quot;$title\&quot;&quot;;
		}
	
		$link_text = $this-&gt;runSpanGamut($link_text);
		$result .= &quot;&gt;$link_text&lt;/a&gt;&quot;;
		$result = $this-&gt;hashPart($result);
	}
	else {
		$result = $whole_match;
	}
	return $result;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doAutoLinks_email_callback"><small>public</small>  _doAutoLinks_email_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doAutoLinks_email_callback($matches) {
	$address = $matches[1];
	$link = $this-&gt;encodeEmailAddress($address);
	return $this-&gt;hashPart($link);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doAutoLinks_url_callback"><small>public</small>  _doAutoLinks_url_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doAutoLinks_url_callback($matches) {
	$url = $this-&gt;encodeAttribute($matches[1]);
	$link = &quot;&lt;a href=\&quot;$url\&quot;&gt;$url&lt;/a&gt;&quot;;
	return $this-&gt;hashPart($link);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doBlockQuotes_callback"><small>public</small>  _doBlockQuotes_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doBlockQuotes_callback($matches) {
	$bq = $matches[1];
	# trim one level of quoting - trim whitespace-only lines
	$bq = preg_replace(&#039;/^[ ]*&gt;[ ]?|^[ ]+$/m&#039;, &#039;&#039;, $bq);
	$bq = $this-&gt;runBlockGamut($bq);		# recurse

	$bq = preg_replace(&#039;/^/m&#039;, &quot;  &quot;, $bq);
	# These leading spaces cause problem with &lt;pre&gt; content, 
	# so we need to fix that:
	$bq = preg_replace_callback(&#039;{(\s*&lt;pre&gt;.+?&lt;/pre&gt;)}sx&#039;, 
		[&amp;$this, &#039;_DoBlockQuotes_callback2&#039;], $bq);

	return &quot;\n&quot;. $this-&gt;hashBlock(&quot;&lt;blockquote&gt;\n$bq\n&lt;/blockquote&gt;&quot;).&quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doBlockQuotes_callback2"><small>public</small>  _doBlockQuotes_callback2()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doBlockQuotes_callback2($matches) {
	$pre = $matches[1];
	$pre = preg_replace(&#039;/^  /m&#039;, &#039;&#039;, $pre);
	return $pre;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doCodeBlocks_callback"><small>public</small>  _doCodeBlocks_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doCodeBlocks_callback($matches) {
	$codeblock = $matches[1];

	$codeblock = $this-&gt;outdent($codeblock);
	$codeblock = htmlspecialchars($codeblock, ENT_NOQUOTES);

	# trim leading newlines and trailing newlines
	$codeblock = preg_replace(&#039;/\A\n+|\n+\z/&#039;, &#039;&#039;, $codeblock);

	$codeblock = &quot;&lt;pre&gt;&lt;code&gt;$codeblock\n&lt;/code&gt;&lt;/pre&gt;&quot;;
	return &quot;\n\n&quot;.$this-&gt;hashBlock($codeblock).&quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doHardBreaks_callback"><small>public</small>  _doHardBreaks_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doHardBreaks_callback($matches) {
	return $this-&gt;hashPart(&quot;&lt;br$this-&gt;empty_element_suffix\n&quot;);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doImages_inline_callback"><small>public</small>  _doImages_inline_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doImages_inline_callback($matches) {
	$whole_match	= $matches[1];
	$alt_text		= $matches[2];
	$url			= $matches[3] == &#039;&#039; ? $matches[4] : $matches[3];
	$title			=&amp; $matches[7];

	$alt_text = $this-&gt;encodeAttribute($alt_text);
	$url = $this-&gt;encodeAttribute($url);
	$result = &quot;&lt;img src=\&quot;$url\&quot; alt=\&quot;$alt_text\&quot;&quot;;
	if (isset($title)) {
		$title = $this-&gt;encodeAttribute($title);
		$result .=  &quot; title=\&quot;$title\&quot;&quot;; # $title already quoted
	}
	$result .= $this-&gt;empty_element_suffix;

	return $this-&gt;hashPart($result);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doImages_reference_callback"><small>public</small>  _doImages_reference_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doImages_reference_callback($matches) {
	$whole_match = $matches[1];
	$alt_text    = $matches[2];
	$link_id     = strtolower($matches[3]);

	if ($link_id == &quot;&quot;) {
		$link_id = strtolower($alt_text); # for shortcut links like ![this][].
	}

	$alt_text = $this-&gt;encodeAttribute($alt_text);
	if (isset($this-&gt;urls[$link_id])) {
		$url = $this-&gt;encodeAttribute($this-&gt;urls[$link_id]);
		$result = &quot;&lt;img src=\&quot;$url\&quot; alt=\&quot;$alt_text\&quot;&quot;;
		if (isset($this-&gt;titles[$link_id])) {
			$title = $this-&gt;titles[$link_id];
			$title = $this-&gt;encodeAttribute($title);
			$result .=  &quot; title=\&quot;$title\&quot;&quot;;
		}
		$result .= $this-&gt;empty_element_suffix;
		$result = $this-&gt;hashPart($result);
	}
	else {
		# If there&#039;s no such link ID, leave intact:
		$result = $whole_match;
	}

	return $result;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_doLists_callback"><small>public</small>  _doLists_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _doLists_callback($matches) {
	# Re-usable patterns to match list item bullets and number markers:
	$marker_ul_re  = &#039;[*+-]&#039;;
	$marker_ol_re  = &#039;\d+[.]&#039;;
	$marker_any_re = &quot;(?:$marker_ul_re|$marker_ol_re)&quot;;
	
	$list = $matches[1];
	$list_type = preg_match(&quot;/$marker_ul_re/&quot;, $matches[3]) ? &quot;ul&quot; : &quot;ol&quot;;
	
	$marker_any_re = ( $list_type == &quot;ul&quot; ? $marker_ul_re : $marker_ol_re );
	
	$list .= &quot;\n&quot;;
	$result = $this-&gt;processListItems($list, $marker_any_re);
	
	$result = $this-&gt;hashBlock(&quot;&lt;$list_type&gt;\n&quot; . $result . &quot;&lt;/$list_type&gt;&quot;);
	return &quot;\n&quot;. $result .&quot;\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_hashHTMLBlocks_callback"><small>public</small>  _hashHTMLBlocks_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _hashHTMLBlocks_callback($matches) {
	$text = $matches[1];
	$key  = $this-&gt;hashBlock($text);
	return &quot;\n\n$key\n\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_initDetab"><small>public</small>  _initDetab()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _initDetab() {
#
# Check for the availability of the function in the `utf8_strlen` property
# (initially `mb_strlen`). If the function is not available, create a 
# function that will loosely count the number of UTF-8 characters with a
# regular expression.
#
	if (function_exists($this-&gt;utf8_strlen)) return;
	$this-&gt;utf8_strlen = function($text) {
		return preg_match_all(&#039;/[\x00-\xBF]|[\xC0-\xFF][\x80-\xBF]*/&#039;, $text, $m);
	};
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_processListItems_callback"><small>public</small>  _processListItems_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _processListItems_callback($matches) {
	$item = $matches[4];
	$leading_line =&amp; $matches[1];
	$leading_space =&amp; $matches[2];
	$marker_space = $matches[3];
	$tailing_blank_line =&amp; $matches[5];

	if ($leading_line || $tailing_blank_line || 
		preg_match(&#039;/\n{2,}/&#039;, $item))
	{
		# Replace marker with the appropriate whitespace indentation
		$item = $leading_space . str_repeat(&#039; &#039;, strlen($marker_space)) . $item;
		$item = $this-&gt;runBlockGamut($this-&gt;outdent($item).&quot;\n&quot;);
	}
	else {
		# Recursion for sub-lists:
		$item = $this-&gt;doLists($this-&gt;outdent($item));
		$item = preg_replace(&#039;/\n+$/&#039;, &#039;&#039;, $item);
		$item = $this-&gt;runSpanGamut($item);
	}

	return &quot;&lt;li&gt;&quot; . $item . &quot;&lt;/li&gt;\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_stripLinkDefinitions_callback"><small>public</small>  _stripLinkDefinitions_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _stripLinkDefinitions_callback($matches) {
	$link_id = strtolower($matches[1]);
	$this-&gt;urls[$link_id] = $matches[2];
	$this-&gt;titles[$link_id] =&amp; $matches[3];
	return &#039;&#039;; # String that will replace the block
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="_unhash_callback"><small>public</small>  _unhash_callback()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function _unhash_callback($matches) {
	return $this-&gt;html_hashes[$matches[0]];
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="detab"><small>public</small>  detab()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function detab($text) {
#
# Replace tabs with the appropriate amount of space.
#
	# For each line we separate the line in blocks delemited by
	# tab characters. Then we reconstruct every line by adding the 
	# appropriate number of space between each blocks.
	
	$text = preg_replace_callback(&#039;/^.*\t.*$/m&#039;,
		[&amp;$this, &#039;_detab_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doAnchors"><small>public</small>  doAnchors()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doAnchors($text) {
#
# Turn Markdown link shortcuts into XHTML &lt;a&gt; tags.
#
	if ($this-&gt;in_anchor) return $text;
	$this-&gt;in_anchor = true;
	
	#
	# First, handle reference-style links: [link text] [id]
	#
	$text = preg_replace_callback(&#039;{
		(					# wrap whole match in $1
		  \[
			(&#039;.$this-&gt;nested_brackets_re.&#039;)	# link text = $2
		  \]

		  [ ]?				# one optional space
		  (?:\n[ ]*)?		# one optional newline followed by spaces

		  \[
			(.*?)		# id = $3
		  \]
		)
		}xs&#039;,
		[&amp;$this, &#039;_doAnchors_reference_callback&#039;], $text);

	#
	# Next, inline-style links: [link text](url &quot;optional title&quot;)
	#
	$text = preg_replace_callback(&#039;{
		(				# wrap whole match in $1
		  \[
			(&#039;.$this-&gt;nested_brackets_re.&#039;)	# link text = $2
		  \]
		  \(			# literal paren
			[ ]*
			(?:
				&lt;(\S*)&gt;	# href = $3
			|
				(&#039;.$this-&gt;nested_url_parenthesis_re.&#039;)	# href = $4
			)
			[ ]*
			(			# $5
			  ([\&#039;&quot;])	# quote char = $6
			  (.*?)		# Title = $7
			  \6		# matching quote
			  [ ]*	# ignore any spaces/tabs between closing quote and )
			)?			# title is optional
		  \)
		)
		}xs&#039;,
		[&amp;$this, &#039;_DoAnchors_inline_callback&#039;], $text);

	#
	# Last, handle reference-style shortcuts: [link text]
	# These must come last in case you&#039;ve also got [link test][1]
	# or [link test](/foo)
	#
/		$text = preg_replace_callback(&#039;{
/			(					# wrap whole match in $1
/			  \[
/				([^\[\]]+)		# link text = $2; can\&#039;t contain [ or ]
/			  \]
/			)
/			}xs&#039;,
/			array(&amp;$this, &#039;_doAnchors_reference_callback&#039;), $text);

	$this-&gt;in_anchor = false;
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doAutoLinks"><small>public</small>  doAutoLinks()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doAutoLinks($text) {
	$text = preg_replace_callback(&#039;{&lt;((https?|ftp|dict):[^\&#039;&quot;&gt;\s]+)&gt;}i&#039;, 
		[&amp;$this, &#039;_doAutoLinks_url_callback&#039;], $text);

	# Email addresses: &lt;address@domain.foo&gt;
	$text = preg_replace_callback(&#039;{
		&lt;
		(?:mailto:)?
		(
			[-.\w\x80-\xFF]+
			\@
			[-a-z0-9\x80-\xFF]+(\.[-a-z0-9\x80-\xFF]+)*\.[a-z]+
		)
		&gt;
		}xi&#039;,
		[&amp;$this, &#039;_doAutoLinks_email_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doBlockQuotes"><small>public</small>  doBlockQuotes()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doBlockQuotes($text) {
	$text = preg_replace_callback(&#039;/
		  (								# Wrap whole match in $1
			(?&gt;
			  ^[ ]*&gt;[ ]?			# &quot;&gt;&quot; at the start of a line
				.+\n					# rest of the first line
			  (.+\n)*					# subsequent consecutive lines
			  \n*						# blanks
			)+
		  )
		/xm&#039;,
		[&amp;$this, &#039;_doBlockQuotes_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doCodeBlocks"><small>public</small>  doCodeBlocks()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doCodeBlocks($text) {
#
#	Process Markdown `&lt;pre&gt;&lt;code&gt;` blocks.
#
	$text = preg_replace_callback(&#039;{
			(?:\n\n|\A\n?)
			(	            # $1 = the code block -- one or more lines, starting with a space/tab
			  (?&gt;
				[ ]{&#039;.$this-&gt;tab_width.&#039;}  # Lines must start with a tab or a tab-width of spaces
				.*\n+
			  )+
			)
			((?=^[ ]{0,&#039;.$this-&gt;tab_width.&#039;}\S)|\Z)	# Lookahead for non-space at line-start, or end of doc
		}xm&#039;,
		[&amp;$this, &#039;_doCodeBlocks_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doHardBreaks"><small>public</small>  doHardBreaks()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doHardBreaks($text) {
	# Do hard breaks:
	return preg_replace_callback(&#039;/ {2,}\n/&#039;, 
		[&amp;$this, &#039;_doHardBreaks_callback&#039;], $text);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doHorizontalRules"><small>public</small>  doHorizontalRules()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doHorizontalRules($text) {
	# Do Horizontal Rules:
	return preg_replace(
		&#039;{
			^[ ]{0,3}	# Leading space
			([-*_])		# $1: First marker
			(?&gt;			# Repeated marker group
				[ ]{0,2}	# Zero, one, or two spaces.
				\1			# Marker character
			){2,}		# Group repeated at least twice
			[ ]*		# Tailing spaces
			$			# End of line.
		}mx&#039;,
		&quot;\n&quot;.$this-&gt;hashBlock(&quot;&lt;hr$this-&gt;empty_element_suffix&quot;).&quot;\n&quot;, 
		$text);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doImages"><small>public</small>  doImages()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doImages($text) {
#
# Turn Markdown image shortcuts into &lt;img&gt; tags.
#
	#
	# First, handle reference-style labeled images: ![alt text][id]
	#
	$text = preg_replace_callback(&#039;{
		(				# wrap whole match in $1
		  !\[
			(&#039;.$this-&gt;nested_brackets_re.&#039;)		# alt text = $2
		  \]

		  [ ]?				# one optional space
		  (?:\n[ ]*)?		# one optional newline followed by spaces

		  \[
			(.*?)		# id = $3
		  \]

		)
		}xs&#039;, 
		[&amp;$this, &#039;_doImages_reference_callback&#039;], $text);

	#
	# Next, handle inline images:  ![alt text](url &quot;optional title&quot;)
	# Don&#039;t forget: encode * and _
	#
	$text = preg_replace_callback(&#039;{
		(				# wrap whole match in $1
		  !\[
			(&#039;.$this-&gt;nested_brackets_re.&#039;)		# alt text = $2
		  \]
		  \s?			# One optional whitespace character
		  \(			# literal paren
			[ ]*
			(?:
				&lt;(\S*)&gt;	# src url = $3
			|
				(&#039;.$this-&gt;nested_url_parenthesis_re.&#039;)	# src url = $4
			)
			[ ]*
			(			# $5
			  ([\&#039;&quot;])	# quote char = $6
			  (.*?)		# title = $7
			  \6		# matching quote
			  [ ]*
			)?			# title is optional
		  \)
		)
		}xs&#039;,
		[&amp;$this, &#039;_doImages_inline_callback&#039;], $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doItalicsAndBold"><small>public</small>  doItalicsAndBold()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doItalicsAndBold($text) {
	$token_stack = [&#039;&#039;];
	$text_stack = [&#039;&#039;];
	$em = &#039;&#039;;
	$strong = &#039;&#039;;
	$tree_char_em = false;
	
	while (1) {
		#
		# Get prepared regular expression for seraching emphasis tokens
		# in current context.
		#
		$token_re = $this-&gt;em_strong_prepared_relist[&quot;$em$strong&quot;];
		
		#
		# Each loop iteration seach for the next emphasis token. 
		# Each token is then passed to handleSpanToken.
		#
		$parts = preg_split($token_re, $text, 2, PREG_SPLIT_DELIM_CAPTURE);
		$text_stack[0] .= $parts[0];
		$token =&amp; $parts[1];
		$text =&amp; $parts[2];
		
		if (empty($token)) {
			# Reached end of text span: empty stack without emitting.
			# any more emphasis.
			while ($token_stack[0]) {
				$text_stack[1] .= array_shift($token_stack);
				$text_stack[0] .= array_shift($text_stack);
			}
			break;
		}
		
		$token_len = strlen($token);
		if ($tree_char_em) {
			# Reached closing marker while inside a three-char emphasis.
			if ($token_len == 3) {
				# Three-char closing marker, close em and strong.
				array_shift($token_stack);
				$span = array_shift($text_stack);
				$span = $this-&gt;runSpanGamut($span);
				$span = &quot;&lt;strong&gt;&lt;em&gt;$span&lt;/em&gt;&lt;/strong&gt;&quot;;
				$text_stack[0] .= $this-&gt;hashPart($span);
				$em = &#039;&#039;;
				$strong = &#039;&#039;;
			} else {
				# Other closing marker: close one em or strong and
				# change current token state to match the other
				$token_stack[0] = str_repeat($token{0}, 3-$token_len);
				$tag = $token_len == 2 ? &quot;strong&quot; : &quot;em&quot;;
				$span = $text_stack[0];
				$span = $this-&gt;runSpanGamut($span);
				$span = &quot;&lt;$tag&gt;$span&lt;/$tag&gt;&quot;;
				$text_stack[0] = $this-&gt;hashPart($span);
				$$tag = &#039;&#039;; # $$tag stands for $em or $strong
			}
			$tree_char_em = false;
		} else if ($token_len == 3) {
			if ($em) {
				# Reached closing marker for both em and strong.
				# Closing strong marker:
				for ($i = 0; $i &lt; 2; ++$i) {
					$shifted_token = array_shift($token_stack);
					$tag = strlen($shifted_token) == 2 ? &quot;strong&quot; : &quot;em&quot;;
					$span = array_shift($text_stack);
					$span = $this-&gt;runSpanGamut($span);
					$span = &quot;&lt;$tag&gt;$span&lt;/$tag&gt;&quot;;
					$text_stack[0] .= $this-&gt;hashPart($span);
					$$tag = &#039;&#039;; # $$tag stands for $em or $strong
				}
			} else {
				# Reached opening three-char emphasis marker. Push on token 
				# stack; will be handled by the special condition above.
				$em = $token{0};
				$strong = &quot;$em$em&quot;;
				array_unshift($token_stack, $token);
				array_unshift($text_stack, &#039;&#039;);
				$tree_char_em = true;
			}
		} else if ($token_len == 2) {
			if ($strong) {
				# Unwind any dangling emphasis marker:
				if (strlen($token_stack[0]) == 1) {
					$text_stack[1] .= array_shift($token_stack);
					$text_stack[0] .= array_shift($text_stack);
				}
				# Closing strong marker:
				array_shift($token_stack);
				$span = array_shift($text_stack);
				$span = $this-&gt;runSpanGamut($span);
				$span = &quot;&lt;strong&gt;$span&lt;/strong&gt;&quot;;
				$text_stack[0] .= $this-&gt;hashPart($span);
				$strong = &#039;&#039;;
			} else {
				array_unshift($token_stack, $token);
				array_unshift($text_stack, &#039;&#039;);
				$strong = $token;
			}
		} else {
			# Here $token_len == 1
			if ($em) {
				if (strlen($token_stack[0]) == 1) {
					# Closing emphasis marker:
					array_shift($token_stack);
					$span = array_shift($text_stack);
					$span = $this-&gt;runSpanGamut($span);
					$span = &quot;&lt;em&gt;$span&lt;/em&gt;&quot;;
					$text_stack[0] .= $this-&gt;hashPart($span);
					$em = &#039;&#039;;
				} else {
					$text_stack[0] .= $token;
				}
			} else {
				array_unshift($token_stack, $token);
				array_unshift($text_stack, &#039;&#039;);
				$em = $token;
			}
		}
	}
	return $text_stack[0];
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="doLists"><small>public</small>  doLists()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function doLists($text) {
#
# Form HTML ordered (numbered) and unordered (bulleted) lists.
#
	$less_than_tab = $this-&gt;tab_width - 1;

	# Re-usable patterns to match list item bullets and number markers:
	$marker_ul_re  = &#039;[*+-]&#039;;
	$marker_ol_re  = &#039;\d+[.]&#039;;
	$marker_any_re = &quot;(?:$marker_ul_re|$marker_ol_re)&quot;;

	$markers_relist = [$marker_ul_re, $marker_ol_re];

	foreach ($markers_relist as $marker_re) {
		# Re-usable pattern to match any entirel ul or ol list:
		$whole_list_re = &#039;
			(								# $1 = whole list
			  (								# $2
				[ ]{0,&#039;.$less_than_tab.&#039;}
				(&#039;.$marker_re.&#039;)			# $3 = first list item marker
				[ ]+
			  )
			  (?s:.+?)
			  (								# $4
				  \z
				|
				  \n{2,}
				  (?=\S)
				  (?!						# Negative lookahead for another list item marker
					[ ]*
					&#039;.$marker_re.&#039;[ ]+
				  )
			  )
			)
		&#039;; // mx
		
		# We use a different prefix before nested lists than top-level lists.
		# See extended comment in _ProcessListItems().
	
		if ($this-&gt;list_level) {
			$text = preg_replace_callback(&#039;{
					^
					&#039;.$whole_list_re.&#039;
				}mx&#039;,
				[&amp;$this, &#039;_doLists_callback&#039;], $text);
		}
		else {
			$text = preg_replace_callback(&#039;{
					(?:(?&lt;=\n)\n|\A\n?) # Must eat the newline
					&#039;.$whole_list_re.&#039;
				}mx&#039;,
				[&amp;$this, &#039;_doLists_callback&#039;], $text);
		}
	}

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="encodeAmpsAndAngles"><small>public</small>  encodeAmpsAndAngles()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function encodeAmpsAndAngles($text) {
#
# Smart processing for ampersands and angle brackets that need to 
# be encoded. Valid character entities are left alone unless the
# no-entities mode is set.
#
	if ($this-&gt;no_entities) {
		$text = str_replace(&#039;&amp;&#039;, &#039;&amp;amp;&#039;, $text);
	} else {
		# Ampersand-encoding based entirely on Nat Irons&#039;s Amputator
		# MT plugin: &lt;http://bumppo.net/projects/amputator/&gt;
		$text = preg_replace(&#039;/&amp;(?!#?[xX]?(?:[0-9a-fA-F]+|\w+);)/&#039;, 
							&#039;&amp;amp;&#039;, $text);
	}
	# Encode remaining &lt;&#039;s
	$text = str_replace(&#039;&lt;&#039;, &#039;&amp;lt;&#039;, $text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="encodeAttribute"><small>public</small>  encodeAttribute()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function encodeAttribute($text) {
#
# Encode text for a double-quoted HTML attribute. This function
# is *not* suitable for attributes enclosed in single quotes.
#
	$text = $this-&gt;encodeAmpsAndAngles($text);
	$text = str_replace(&#039;&quot;&#039;, &#039;&amp;quot;&#039;, $text);
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="encodeEmailAddress"><small>public</small>  encodeEmailAddress()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function encodeEmailAddress($addr) {
#
#	Input: an email address, e.g. &quot;foo@example.com&quot;
#
#	Output: the email address as a mailto link, with each character
#		of the address encoded as either a decimal or hex entity, in
#		the hopes of foiling most address harvesting spam bots. E.g.:
#
#	  &lt;p&gt;&lt;a href=&quot;&amp;#109;&amp;#x61;&amp;#105;&amp;#x6c;&amp;#116;&amp;#x6f;&amp;#58;&amp;#x66;o&amp;#111;
#        &amp;#x40;&amp;#101;&amp;#x78;&amp;#97;&amp;#x6d;&amp;#112;&amp;#x6c;&amp;#101;&amp;#46;&amp;#x63;&amp;#111;
#        &amp;#x6d;&quot;&gt;&amp;#x66;o&amp;#111;&amp;#x40;&amp;#101;&amp;#x78;&amp;#97;&amp;#x6d;&amp;#112;&amp;#x6c;
#        &amp;#101;&amp;#46;&amp;#x63;&amp;#111;&amp;#x6d;&lt;/a&gt;&lt;/p&gt;
#
#	Based by a filter by Matthew Wickline, posted to BBEdit-Talk.
#   With some optimizations by Milian Wolff.
#
	$addr = &quot;mailto:&quot; . $addr;
	$chars = preg_split(&#039;/(?&lt;!^)(?!$)/&#039;, $addr);
	$seed = (int)abs(crc32($addr) / strlen($addr)); # Deterministic seed.
	
	foreach ($chars as $key =&gt; $char) {
		$ord = ord($char);
		# Ignore non-ascii chars.
		if ($ord &lt; 128) {
			$r = ($seed * (1 + $key)) % 100; # Pseudo-random function.
			# roughly 10% raw, 45% hex, 45% dec
			# &#039;@&#039; *must* be encoded. I insist.
			if ($r &gt; 90 &amp;&amp; $char != &#039;@&#039;) /* do nothing */;
			else if ($r &lt; 45) $chars[$key] = &#039;&amp;#x&#039;.dechex($ord).&#039;;&#039;;
			else              $chars[$key] = &#039;&amp;#&#039;.$ord.&#039;;&#039;;
		}
	}
	
	$addr = implode(&#039;&#039;, $chars);
	$text = implode(&#039;&#039;, array_slice($chars, 7)); # text without `mailto:`
	$addr = &quot;&lt;a href=\&quot;$addr\&quot;&gt;$text&lt;/a&gt;&quot;;

	return $addr;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="handleSpanToken"><small>public</small>  handleSpanToken()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function handleSpanToken($token, &amp;$str) {
#
# Handle $token provided by parseSpan by determining its nature and 
# returning the corresponding value that should replace it.
#
	switch ($token{0}) {
		case &quot;\\&quot;:
			return $this-&gt;hashPart(&quot;&amp;#&quot;. ord($token{1}). &quot;;&quot;);
		case &quot;`&quot;:
			# Search for end marker in remaining text.
			if (preg_match(&#039;/^(.*?[^`])&#039;.preg_quote($token).&#039;(?!`)(.*)$/sm&#039;, 
				$str, $matches))
			{
				$str = $matches[2];
				$codespan = $this-&gt;makeCodeSpan($matches[1]);
				return $this-&gt;hashPart($codespan);
			}
			return $token; // return as text since no ending marker found.
		default:
			return $this-&gt;hashPart($token);
	}
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="hashBlock"><small>public</small>  hashBlock()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function hashBlock($text) {
#
# Shortcut function for hashPart with block-level boundaries.
#
	return $this-&gt;hashPart($text, &#039;B&#039;);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="hashPart"><small>public</small>  hashPart()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function hashPart($text, $boundary = &#039;X&#039;) {
#
# Called whenever a tag must be hashed when a function insert an atomic 
# element in the text stream. Passing $text to through this function gives
# a unique text-token which will be reverted back when calling unhash.
#
# The $boundary argument specify what character should be used to surround
# the token. By convension, &quot;B&quot; is used for block elements that needs not
# to be wrapped into paragraph tags at the end, &quot;:&quot; is used for elements
# that are word separators and &quot;X&quot; is used in the general case.
#
	# Swap back any tag hash found in $text so we do not have to `unhash`
	# multiple times at the end.
	$text = $this-&gt;unhash($text);
	
	# Then hash the block.
	static $i = 0;
	$key = &quot;$boundary\x1A&quot; . ++$i . $boundary;
	$this-&gt;html_hashes[$key] = $text;
	return $key; # String that will replace the tag.
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="makeCodeSpan"><small>public</small>  makeCodeSpan()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function makeCodeSpan($code) {
#
# Create a code span markup for $code. Called from handleSpanToken.
#
	$code = htmlspecialchars(trim($code), ENT_NOQUOTES);
	return $this-&gt;hashPart(&quot;&lt;code&gt;$code&lt;/code&gt;&quot;);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="outdent"><small>public</small>  outdent()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function outdent($text) {
#
# Remove one level of line-leading tabs or spaces
#
	return preg_replace(&#039;/^(\t|[ ]{1,&#039;.$this-&gt;tab_width.&#039;})/m&#039;, &#039;&#039;, $text);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="parseSpan"><small>public</small>  parseSpan()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function parseSpan($str) {
#
# Take the string $str and parse it into tokens, hashing embeded HTML,
# escaped characters and handling code spans.
#
	$output = &#039;&#039;;
	
	$span_re = &#039;{
			(
				\\\\&#039;.$this-&gt;escape_chars_re.&#039;
			|
				(?&lt;![`\\\\])
				`+						# code span marker
		&#039;.( $this-&gt;no_markup ? &#039;&#039; : &#039;
			|
				&lt;!--    .*?     --&gt;		# comment
			|
				&lt;\?.*?\?&gt; | &lt;%.*?%&gt;		# processing instruction
			|
				&lt;[/!$]?[-a-zA-Z0-9:]+	# regular tags
				(?&gt;
					\s
					(?&gt;[^&quot;\&#039;&gt;]+|&quot;[^&quot;]*&quot;|\&#039;[^\&#039;]*\&#039;)*
				)?
				&gt;
		&#039;).&#039;
			)
			}xs&#039;;

	while (1) {
		#
		# Each loop iteration seach for either the next tag, the next 
		# openning code span marker, or the next escaped character. 
		# Each token is then passed to handleSpanToken.
		#
		$parts = preg_split($span_re, $str, 2, PREG_SPLIT_DELIM_CAPTURE);
		
		# Create token from text preceding tag.
		if ($parts[0] != &quot;&quot;) {
			$output .= $parts[0];
		}
		
		# Check if we reach the end.
		if (isset($parts[1])) {
			$output .= $this-&gt;handleSpanToken($parts[1], $parts[2]);
			$str = $parts[2];
		}
		else {
			break;
		}
	}
	
	return $output;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="prepareItalicsAndBold"><small>public</small>  prepareItalicsAndBold()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function prepareItalicsAndBold() {
#
# Prepare regular expressions for seraching emphasis tokens in any
# context.
#
	foreach ($this-&gt;em_relist as $em =&gt; $em_re) {
		foreach ($this-&gt;strong_relist as $strong =&gt; $strong_re) {
			# Construct list of allowed token expressions.
			$token_relist = [];
			if (isset($this-&gt;em_strong_relist[&quot;$em$strong&quot;])) {
				$token_relist[] = $this-&gt;em_strong_relist[&quot;$em$strong&quot;];
			}
			$token_relist[] = $em_re;
			$token_relist[] = $strong_re;
			
			# Construct master expression from list.
			$token_re = &#039;{(&#039;. implode(&#039;|&#039;, $token_relist) .&#039;)}&#039;;
			$this-&gt;em_strong_prepared_relist[&quot;$em$strong&quot;] = $token_re;
		}
	}
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="processListItems"><small>public</small>  processListItems()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function processListItems($list_str, $marker_any_re) {
#
#	Process the contents of a single ordered or unordered list, splitting it
#	into individual list items.
#
	# The $this-&gt;list_level global keeps track of when we&#039;re inside a list.
	# Each time we enter a list, we increment it; when we leave a list,
	# we decrement. If it&#039;s zero, we&#039;re not in a list anymore.
	#
	# We do this because when we&#039;re not inside a list, we want to treat
	# something like this:
	#
	#		I recommend upgrading to version
	#		8. Oops, now this line is treated
	#		as a sub-list.
	#
	# As a single paragraph, despite the fact that the second line starts
	# with a digit-period-space sequence.
	#
	# Whereas when we&#039;re inside a list (or sub-list), that line will be
	# treated as the start of a sub-list. What a kludge, huh? This is
	# an aspect of Markdown&#039;s syntax that&#039;s hard to parse perfectly
	# without resorting to mind-reading. Perhaps the solution is to
	# change the syntax rules such that sub-lists must start with a
	# starting cardinal number; e.g. &quot;1.&quot; or &quot;a.&quot;.
	
	$this-&gt;list_level++;

	# trim trailing blank lines:
	$list_str = preg_replace(&quot;/\n{2,}\\z/&quot;, &quot;\n&quot;, $list_str);

	$list_str = preg_replace_callback(&#039;{
		(\n)?							# leading line = $1
		(^[ ]*)							# leading whitespace = $2
		(&#039;.$marker_any_re.&#039;				# list marker and space = $3
			(?:[ ]+|(?=\n))	# space only required if item is not empty
		)
		((?s:.*?))						# list item text   = $4
		(?:(\n+(?=\n))|\n)				# tailing blank line = $5
		(?= \n* (\z | \2 (&#039;.$marker_any_re.&#039;) (?:[ ]+|(?=\n))))
		}xm&#039;,
		[&amp;$this, &#039;_processListItems_callback&#039;], $list_str);

	$this-&gt;list_level--;
	return $list_str;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="runBasicBlockGamut"><small>public</small>  runBasicBlockGamut()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function runBasicBlockGamut($text) {
#
# Run block gamut tranformations, without hashing HTML blocks. This is 
# useful when HTML blocks are known to be already hashed, like in the first
# whole-document pass.
#
	foreach ($this-&gt;block_gamut as $method =&gt; $priority) {
		$text = $this-&gt;$method($text);
	}
	
	# Finally form paragraph and restore hashed blocks.
	$text = $this-&gt;formParagraphs($text);

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="runBlockGamut"><small>public</small>  runBlockGamut()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function runBlockGamut($text) {
#
# Run block gamut tranformations.
#
	# We need to escape raw HTML in Markdown source before doing anything 
	# else. This need to be done for each block, and not only at the 
	# begining in the Markdown function since hashed blocks can be part of
	# list items and could have been indented. Indented blocks would have 
	# been seen as a code block in a previous pass of hashHTMLBlocks.
	$text = $this-&gt;hashHTMLBlocks($text);
	
	return $this-&gt;runBasicBlockGamut($text);
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="runSpanGamut"><small>public</small>  runSpanGamut()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function runSpanGamut($text) {
#
# Run span gamut tranformations.
#
	foreach ($this-&gt;span_gamut as $method =&gt; $priority) {
		$text = $this-&gt;$method($text);
	}

	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="stripLinkDefinitions"><small>public</small>  stripLinkDefinitions()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function stripLinkDefinitions($text) {
#
# Strips link definitions from text, stores the URLs and titles in
# hash references.
#
	$less_than_tab = $this-&gt;tab_width - 1;

	# Link defs are in the form: ^[id]: url &quot;optional title&quot;
	$text = preg_replace_callback(&#039;{
						^[ ]{0,&#039;.$less_than_tab.&#039;}\[(.+)\][ ]?:	# id = $1
						  [ ]*
						  \n?				# maybe *one* newline
						  [ ]*
						&lt;?(\S+?)&gt;?			# url = $2
						  [ ]*
						  \n?				# maybe one newline
						  [ ]*
						(?:
							(?&lt;=\s)			# lookbehind for whitespace
							[&quot;(]
							(.*?)			# title = $3
							[&quot;)]
							[ ]*
						)?	# title is optional
						(?:\n+|\Z)
		}xm&#039;,
		[&amp;$this, &#039;_stripLinkDefinitions_callback&#039;],
		$text);
	return $text;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="transform"><small>public</small>  transform()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function transform($text) {
#
# Main function. Performs some preprocessing on the input text
# and pass it through the document gamut.
#
	$this-&gt;setup();

	# Remove UTF-8 BOM and marker character in input, if present.
	$text = preg_replace(&#039;{^\xEF\xBB\xBF|\x1A}&#039;, &#039;&#039;, $text);

	# Standardize line endings:
	#   DOS to Unix and Mac to Unix
	$text = preg_replace(&#039;{\r\n?}&#039;, &quot;\n&quot;, $text);

	# Make sure $text ends with a couple of newlines:
	$text .= &quot;\n\n&quot;;

	# Convert all tabs to spaces.
	$text = $this-&gt;detab($text);

	# Turn block-level HTML blocks into hash entries
	$text = $this-&gt;hashHTMLBlocks($text);

	# Strip any lines consisting only of spaces and tabs.
	# This makes subsequent regexen easier to write, because we can
	# match consecutive blank lines with /\n+/ instead of something
	# contorted like /[ ]*\n+/ .
	$text = preg_replace(&#039;/^[ ]+$/m&#039;, &#039;&#039;, $text);

	# Run document gamut methods.
	foreach ($this-&gt;document_gamut as $method =&gt; $priority) {
		$text = $this-&gt;$method($text);
	}
	
	$this-&gt;teardown();

	return $text . &quot;\n&quot;;
}</code>
</pre>
</div>
</div>

<div class='method'>
<h3 id="unhash"><small>public</small>  unhash()<small> (defined in <a href='/documentation/api/Markdown_Parser'>Markdown_Parser</a>)</small></h3>
<div class='description'></div>
<div class="method-source">
<h4>Source Code</h4>
<pre>
<code class="language-php">function unhash($text) {
#
# Swap back in all the tags hashed by _HashHTMLBlocks.
#
	return preg_replace_callback(&#039;/(.)\x1A[0-9]+\1/&#039;, 
		[&amp;$this, &#039;_unhash_callback&#039;], $text);
}</code>
</pre>
</div>
</div>
</div>