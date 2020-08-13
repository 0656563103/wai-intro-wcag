---
# Translation info https://www.w3.org/wiki/WAI/Website/Translate

title: "What's New in WCAG 2.2 Working Draft"
title_html: "What's New in WCAG 2.2 Working Draft"
nav_title: "New in 2.2 Draft"
doc-note-type: draft
doc-note-message-md: Status: _This page is an in-progress draft_.

description: This page lists the new success criteria in Web Content Accessibility Guidelines (WCAG) 2.2. It includes quotes from personas (fictional people) to help you understand some aspects of the success criteria.

teaser_text: WCAG 2.2 has 9 additional requirements (“success criteria”) that address the needs of people with cognitive or learning disabilities, mobile devices users, and ebook users. The What’s New in WCAG 2.2 page introduces the new success criteria. It includes quotes from personas to help you understand the issues.

lang: en
last_updated: 2020-08-11
permalink: /standards-guidelines/wcag/new-in-22/

github:
  repository: w3c/wai-intro-wcag
  path: 'content/new-in-22.md'

feedbackmail: wai@w3.org
image: /content-images/wai-intro-wcag/general-social.png
footer: >
  <p><strong>Status: In-progress draft.</strong></p>
  <p><strong>Editor:</strong> <a href="https://www.w3.org/People/Shawn/">Shawn Lawton Henry</a>. Contributors: <a href="https://www.w3.org/People/shadi/">Shadi Abou-Zahra</a>,  <a href="https://www.w3.org/groups/wg/eowg/participants">EOWG Participants</a>, and <a href="https://www.w3.org/groups/wg/ag/participants">AG WG Participants</a>.</p>
  <p>Developed with input from the Education and Outreach Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">EOWG</a>) and the Accessibility Guidelines Working Group (<a href="https://www.w3.org/WAI/about/groups/eowg/">AG WG</a>).</p>
inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin-right: 0; margin-bottom:40px;}
  .quotes {margin-bottom:40px;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row; padding-bottom:}
  .quotes li>p span {display:table-cell;}
  .issue {font-weight: bold; display:table-cell; width: 6em;}
  q:before {content: open-quote;color: #005a6a;font-weight: bold;}
  q:after {content: close-quote;color: #005a6a;font-weight: bold;}
  .sc dt {
    display: list-item;
    list-style-type: disc;
    float: left;
    font-weight: bold;
    margin-left: 2em;
    margin-right: 1ex;
    margin-top: 0;
  }
  .sc dt:after {
    content: ":";
  }
  .sc p:last-of-type {margin-bottom: 1em}
  .sc p:last-child, .sc *:last-child {margin-bottom: 0}
  
  
  div.note-title , div.ednote-title, div.warning-title {
      padding-right:  1em;
      min-width: 7.5em;
      color: #b9ab2d;
  }
  div.note-title, div.ednote-title { color: #2b2; }
  div.warning-title { color: #f22; }
  div.note-title span, div.ednote-title span, div.warning-title span {
      text-transform: uppercase;
  }
  div.note, div.ednote, div.warning {
      margin-top: 1em;
      margin-bottom: 1em;
  }
  .note > p:first-child, .ednote > p:first-child,.warning > p:first-child { margin-top: 0 }
  .note, .ednote, .warning {
      padding: .5em;
      border-left-width: .5em;
      border-left-style: solid;
  }
  div.note , div.ednote,  div.warning {
      padding: 1em 1.2em 0.5em;
      margin: 1em 0;
      position: relative;
      clear: both;
  }
  span.note, span.ednote, span.warning { padding: .1em .5em .15em; }
  .note, .ednote {
      border-color: #52e052;
      background: #e9fbe9;
  }

ref: /standards-guidelines/wcag/new-in-22/

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page lists the **proposed** new success criteria in the **Working Draft** of Web Content Accessibility Guidelines (WCAG) 2.2.

**It includes quotes from personas (fictional people)** to help you understand some aspects of the success criteria. It also includes links to Understanding documents that explain the success criteria in detail and provide more examples.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

For an introduction to Web Content Accessibility Guidelines (WCAG) and more about versions 2.0, 2.1, and 2.2, see the [WCAG Overview](/standards-guidelines/wcag/).

All success criteria from 2.0 and 2.1 are included in 2.2. The 2.0 and 2.1 success criteria are exactly the same (verbatim, word-for-word) in 2.2.

WCAG 2.2 Working Draft provides 9 additional success criteria, that are included on this page.

In WCAG 2.2, success criteria **[2.4.7 Focus Visible](https://www.w3.org/TR/WCAG22/#focus-visible) is changed from Level AA to Level A**.

<em>To comment on the WCAG Working Draft:</em> Please submit any comments on these new proposed success criteria by 18 September 2020. Ideally open one [new GitHub issue]( https://github.com/w3c/wcag/issues/new) per discrete comment. If you’re not comfortable with GitHub, you can send comments to public-agwg-comments@w3.org

## Guideline 2.4 Navigable

Provide ways to help users navigate, find content, and determine where they are.

### 2.4.11 Focus Appearance (Minimum) (AA)

<blockquote class="sc">
  <p>For the keyboard focus indicator of each User interface component, all of the following are true:</p>
  <ul>
    <li><strong>Minimum area:</strong> The <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indication-area">focus indication area</a> is greater than or equal to a 1 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixel">CSS pixel</a> border of the focused control, or has a thickness of at least 8 CSS pixels along the shortest side of the element.</li>
    <li><strong>Change of contrast:</strong> The color change for the focus indication area has a contrast ratio of at least 3:1 with the colors of the unfocused state.</li>
    <li><strong>Adjacent contrast:</strong> The focus indication area has a contrast ratio of at least 3:1 against all adjacent colors for the minimum area or greater, or has a thickness of at least 2 CSS pixels.</li>
    <li><strong>Unobscured:</strong> The item with focus is not entirely hidden by author-created content.</li>
</ul>
  <p class="note">A keyboard focus indicator which has a pattern or gradient may have parts that do not meet the 3:1 contrast ratio for the change of contrast, as long as an area equal to the minimum does meet the contrast ratio.</p>
  <p class="note">If the control has a visible boundary smaller than the hit area, the size measure
 is taken from the visible boundary.</p>
  <p class="ednote">The working group is interested in feedback about the minimum area metric, and if there are unusual scenarios where visible indicators are caught by the wording.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who doesn't use a mouse:<br>and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low contrast sensitivity:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I can't tell where the keyboard focus is as I move around a web page or app.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>I can see where the keyboard focus is as I move around a web page or app.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance-minimum.html">Understanding Focus Appearance (Minimum)</a></p>

### 2.4.12 Focus Appearance (Enhanced) (AAA)

<blockquote class="sc">
  <p>For the keyboard focus indicator of each User interface component, all of the following are true:</p>
  <ul>
    <li><strong>Minimum area:</strong> The <a href="https://www.w3.org/TR/WCAG22/#dfn-focus-indication-area">focus indication area</a> is greater than or equal to a 2 <a href="https://www.w3.org/TR/WCAG22/#dfn-css-pixel">CSS pixel</a> solid border around the control.</li>
    <li><strong>Change of contrast:</strong> Color changes used to indicate focus have a contrast ratio of at least 4.5:1 with the colors changed from the unfocused control.</li>
    <li><strong>Unobscured:</strong> No part of the focus indicator is hidden by author-created content.</li>
  </ul>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#reporter">Reporter</a> with repetitive stress injury who doesn't use a mouse:<br>and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low contrast sensitivity:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I can't tell where the keyboard focus is as I move around a web page or app.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>I can easily see where the keyboard focus is as I move around a web page or app.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/focus-appearance-enhanced">Understanding Focus Appearance (Enhanced)</a></p>

### 2.4.13 Fixed Reference Points (A)

<blockquote class="sc">
  <p>When a <a href="https://www.w3.org/TR/WCAG22/#dfn-web-page">web page</a> or <a href="https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages">set of web pages</a> is an <a href="https://www.w3.org/TR/WCAG22/#dfn-electronic-publications">electronic publication</a> with <a href="https://www.w3.org/TR/WCAG22/#dfn-pagebreak-locator">pagebreak locators</a>, a mechanism is available to navigate to each locator and each locator maintains its place in the flow of content, even when the formatting or platform change.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#classroomstudent">Student</a> with dyslexia:<br>and <a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with low vision:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I increase the text size and spacing in the online textbook. The instructor said: "The activity is on page 37." But it's not on page 37 in my view, and I cannot find it.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>I used the page contents list to get to "page 37". (It's actually page 53 in my view — that's OK, I found it.)</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/fixed-reference-points">Understanding Fixed Reference Points</a></p>

## Guideline 2.5 Input Modalities

Make it easier for users to operate functionality through various inputs beyond keyboard.

### 2.5.7 Dragging (AA)

<blockquote class="sc">
  <p>All functionality that uses a <a href="https://www.w3.org/TR/WCAG22/#dfn-dragging-movement">dragging movement</a> for operation can be operated by a single pointer without dragging, unless dragging is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a>.</p>
  <p class="note">This requirement applies to web content that interprets pointer actions (i.e. this does not apply to actions that are required to operate the user agent or assistive technology).</p>
  <p class="ednote">Is there an assistive technology that helps for people with mobility impairments?  The group would like feedback on the frontier between AT &amp; author responsibility.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with hand tremor:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I cannot hold down the mouse button and drag it accurately enough to move the items in this list.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>When I click on an item in the list, I get up and down arrows and I can click those to change the order.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/dragging">Understanding Dragging</a></p>

### 2.5.8 Pointer Target Spacing (AA)

<blockquote class="sc">
  <p>For each <a href="https://www.w3.org/TR/WCAG22/#dfn-target">target</a>, there is an area with a width and height of at least 44 CSS pixels that includes it, and no other targets, except when:</p>
  <ul>
    <li><strong>Enlarge:</strong> A mechanism is available to change the CSS pixel size of each target, or its spacing, so there is an area with a width and height of at least 44 CSS pixels that includes it, and no other targets;</li>
    <li><strong>Inline:</strong> The target is in a sentence or block of text;</li>
    <li><strong>User agent:</strong> The size of the target is controlled by the user agent and is not modified by the author;</li>
    <li><strong>Essential:</strong> A particular presentation of the target is essential to the information being conveyed.</li>
  </ul>
  <p class="note">This criterion has been formulated to increase the hit-area of small targets, but the group would like feedback from providers of touch-screen devices if there is another way of forming the criteria to better complement the tap-heuristics used.</p>
  <p class="note">Are there issues with internationalization when describing inline links?</p>
  <p class="note">Are there issues with pop-over content overlapping targets triggering failures?</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#retiree">Retiree</a> with hand tremor:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>The buttons are so close together, I hit "Cancel" when going for "Submit". Then I have to start all over again.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>There is more space between the buttons so I don't hit the wrong button even when I'm riding on the bumpy bus.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/pointer-target-spacing">Understanding Pointer Target Spacing</a></p>

## Guideline 3.2 Predictable

Make Web pages appear and operate in predictable ways.

### 3.2.6 Findable Help (A)

<blockquote class="sc">
  <p>For <a href="https://www.w3.org/TR/WCAG22/#dfn-single-page-web-application">single page Web applications</a> or any <a href="https://www.w3.org/TR/WCAG22/#dfn-set-of-web-pages">set of Web pages</a>, if one of the following is available, then access to at least one option is included in the <a href="https://www.w3.org/TR/WCAG22/#dfn-same-relative-order">same relative order</a> on each page:</p>
  <ul>
    <li>Human contact details;</li>
    <li>Human contact mechanism;</li>
    <li>Self-help option;</li>
    <li>A fully automated contact mechanism.</li>
  </ul>
  <p class="note">Access to help mechanisms may be provided directly on the page, or may be provided via a direct link to a different page containing the information"</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Whenever I use the online app to schedule my medical appointments, I can't remember what to do at each step. I've see a Chat option in some places, but can't find it now.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>When I need help, I can easily find the Chat option that's always in the lower right corner of the page.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/findable-help">Understanding Findable Help</a></p>

### 3.2.7 Hidden Controls (AA)

<blockquote class="sc">
  <p>Controls needed to progress or complete a <a href="https://www.w3.org/TR/WCAG22/#dfn-process">process</a> are visible at the time they are needed without requiring pointer hover or keyboard focus, or a mechanism is available to make them persistently visible.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I can't tell what options are available. Some buttons appeared when I was mousing around, but now I can't find them.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>The available buttons are all visible, without me having to mouse around.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/hidden-controls">Understanding Hidden Controls</a></p>

## Guideline 3.3 Input Assistance

Help users avoid and correct mistakes.

### 3.3.7 Accessible Authentication (A)

<blockquote class="sc">
  <p> If an authentication process relies on a <a href="https://www.w3.org/TR/WCAG22/#dfn-cognitive-function-test">cognitive function test</a>, at least one other method must also be available that does not rely on a cognitive function test.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>I don't understand what they want me to type in or click on to get into this app.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>I can use my email and password to get into this app.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/accessible-authentication">Understanding Accessible Authentication</a></p>

### 3.3.8 Redundant Entry (A)

<blockquote class="sc">
<p>For steps in a <a href="https://www.w3.org/TR/WCAG22/#dfn-process">process</a>, information previously entered by or provided to the user that is required on subsequent steps is either:</p>
<ul>
  <li>auto-populated, or</li>
  <li>available for the user to select.</li>
</ul>
<p>Exception: When re-entering the information is <a href="https://www.w3.org/TR/WCAG22/#dfn-essential">essential</a>.</p>
<p class="note">Security verification, such as repeating a password, is considered essential.</p>
<p class="note">Editors' note: Are there issues storing the data so a user can access it in subsequent steps?</p>
<p class="note">Editors' note: Are there broader exceptions needed than essential? E.g. for mandated or required information re-entry.</p>
</blockquote>
<p class="persona"><a href="https://www.w3.org/WAI/people-use-web/user-stories/#supermarketassistant">Supermarket assistant</a> with cognitive disabilities:</p>
<div class="quotes">
  <ul>
    <li><p><span class="issue">Problem:</span><span><q>Whenever I use the online app to schedule my medical appointments, I have to re-type some information that I entered in a previous step.</q></span></p></li>
    <li><p><span class="issue">Works well:</span><span><q>The app automatically fills in information that I entered in previous steps.</q></span></p></li>
  </ul>
</div>
<p><a href="https://www.w3.org/WAI/WCAG22/Understanding/redundant-entry">Understanding Redundant Entry</a></p>

## About the Personas Quotes

The linked persona roles go to the [[Stories of Web Users]](/people-use-web/user-stories/). That page has other personas with different disabilities. We might add more in the future.

We plan to add these to the Understanding WCAG documents.
