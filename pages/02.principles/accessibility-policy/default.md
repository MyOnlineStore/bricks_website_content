---
title: 'Accessibility Policy'
visible: true
---

<p><em><span style="font-weight: 400;">Source: </span></em><a href="https://a11yproject.com/checklist"><em><span style="font-weight: 400;">https://a11yproject.com/checklist</span></em></a></p>
<h3 id="mcetoc_1cala42nt0">ARIA landmarks</h3>
<p id="mcetoc_1cala4bs40"><span style="font-weight: 400;">ARIA Landmark roles can help assistive technology users to quickly navigate to and past blocks of content in a web interface. Use these ARIA landmarks:</span></p>
<ul style="list-style-type: circle;">
<li><span style="font-weight: 400;">banner</span></li>
<li><span style="font-weight: 400;">navigation</span></li>
<li><span style="font-weight: 400;">main</span></li>
<li><span style="font-weight: 400;">article</span></li>
<li><span style="font-weight: 400;">complementary</span></li>
<li><span style="font-weight: 400;">contentinfo</span></li>
<li><span style="font-weight: 400;">search</span></li>
</ul>
<hr />
<h3 id="mcetoc_1calaf21q8">Semantics</h3>
<p><em><span style="font-weight: 400;">Use a tool to check for major issues with semantics in HTML. Only applicable on layout and important elements, not on specialized components and details like foldout menu's or the shipping rates component. The goal is to make the majority of all components and resulting DOM semantically correct so it makes sense without stylesheet, on a screenreader or in other situations where the visual representation is secondary to the structure of a page.</span></em></p>
<hr />
<h3 id="mcetoc_1calaf00d7">Links</h3>
<ul>
<li><em><span style="font-weight: 400;">Every link should have a clear :focus state and should be accessible with a keyboard. That way people will not get lost easily and keyboard-first users (like people with a motoric disability) can navigate the system easily.&nbsp;</span></em></li>
<li><em><span style="font-weight: 400;">Every page should have a hidden "jump to content" link to skip the header, navigation and all elements that are redundant in the systems.</span></em></li>
</ul>
<hr />
<h3 id="mcetoc_1calaetuk6">Alternative text</h3>
<ul>
<li><em>All images in the system should have a <strong>usefull&nbsp;</strong>ALT attribute. Don't repeat the filename, but create a usefull description that explains what is visible in the picture or what the goal of the image is. </em></li>
<li><em>SVG includes should contain a title tag which is the SVG alternative for an ALT attribute.</em></li>
</ul>
<hr />
<h3 id="mcetoc_1calaeq1k5">Forms</h3>
<ul>
<li><em><span style="font-weight: 400;">Forms need to have a logical layout and orde. </span></em></li>
<li><em><span style="font-weight: 400;">All fields should have a connected label with a text. </span></em><em><span style="font-weight: 400;">Empty labels are not allowed. </span></em></li>
<li><em><span style="font-weight: 400;">Do not use placeholders as labels. </span></em></li>
<li><em><span style="font-weight: 400;">Formfields need to be grouped in fieldsets when necessary.</span></em></li>
</ul>
<hr />
<h3 id="mcetoc_1calaeni14">Subtitles in video</h3>
<p><em><span style="font-weight: 400;">Add subtitles to our own content, not third party content and only when this is technically possible and in a reasonable time, like Youtube has a tool for adding subtitles.</span></em></p>
<hr />
<h3 id="mcetoc_1calael5r3">Color contrast</h3>
<p><em><span style="font-weight: 400;">Only primary elements need to have a <a href="https://contrastchecker.com/">WCAG AA level contrast</a>. Like a submit button, page header, search box, etc.</span></em></p>
<hr />
<h3 id="mcetoc_1calaeijo2">Keyboard input</h3>
<ul>
<li><em><span style="font-weight: 400;">All components should be reachable with a keyboard</span></em></li>
<li><em>All keyboard elements should have a logical order (tabindex)</em></li>
</ul>
<hr />
<h3 id="mcetoc_1cala731p0">Screen reader</h3>
<ul>
<li><em><span style="font-weight: 400;">Sites should be properly usable with a screen reader.</span></em></li>
<li><em><span style="font-weight: 400;">Invisible elements and decorative elements should be hidden from screen readers (aria-role=hidden).</span></em></li>
<li><em><span style="font-weight: 400;">Declaring a language attribute on the HTML element enables a screen reader to read out the text with correct pronunciation.</span></em></li>
</ul>