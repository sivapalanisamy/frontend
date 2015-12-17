General

  Site uses a cache buster for expiring  .js, .css, and images
  JavaScript and CSS is minified and  concatenated into logical groupings
  Images have been optimized by  ImageOptim (http://imageoptim.com/)

Markup

  Code does not contain inline  JavaScript event listeners
  Code does not contain inline style  attributes
  Code does not contain deprecated  elements &amp; attributes
  Page begins with a valid DTD (HTML5  doctype)
  Code is indented using hard tabs
  Tags and attributes are lowercase
  Tags are closed and nested properly
  Markup is semantic (e.g. class names  do not denote presentation, Items in list form are housed in a UL, OL, or DL)
  Tables are only used to display  tabular data
  Element IDs are unique
  Code validates against the W3C  validator
  DOM nesting depth does not exceed 12  levels
  Total page weight does not exceed  client requirements (e.g. 1000kb)
  TItle case is used for headers/titles  and forced to all caps using the CSS declaration text-transform: uppercase;
  Where text is included via images,  CSS image replacement is used.

Forms

  All user input is &ldquo;sanitized&rdquo;(Make  Clean)
  Form elements are paired with labels  elements containing the for attribute
  Form label/input pairs are wrapped  with a block level element (e.g. &lt;p&gt;)
  Forms are logically arranged within  fieldsets


Accessibility

  Page has a proper outline (H1-H6  order)
  Alt attributes exist on all  &lt;img&gt; elements
  Video is accompanied by a transcript  and closed captioning
  Code validates against WCAG priority  level 1 and 2
  Events and styles applied to :hover  are also applied to :focus
  Tabindex order is logical and  intuitive

CSS

  Style blocks are externalized to .css  files
  Consistent naming conventions are  used
  CSS validates against the W3C  validator
  CSS selectors are only as specific as  they need to be; grouped logically
  A print-friendly .css file is  included in the page
  A reset.css file is included in the  page
  CSS sprites are used to combine  images
  CSS selectors gets more specific  across files
  CSS shorthand is used for properties  that support it
  CSS selectors are not tag qualified
  CSS properties are alphabetical  (except for vendor-specific properties) (Why? See: Parable of the brown  M&amp;Ms)

JavaScript

  Script blocks are externalized to .js  files
  Consistent naming conventions are  used
  Code adheres to the K&amp;R style
  Core page features function with  JavaScript disabled
  JavaScript belongs to a namespace (no  globally scoped code)
  jQuery selectors are performant
  jQuery objects are cached
  Event delegation is used for binding  events to 2 or more elements, or ajax'd elements
  Script blocks are placed before the  closing &lt;body&gt; tag
  Code has been run through JSLint  (jslint.com) or JSHint (jshint.com)

SEO

  Uses a valid &lt;title&gt; element  with a valid text node
  Uses description meta data
  Uses visible header tags

Mobile

  Functions with JavaScript turned off
  Image file sizes do not exceed 70kb
  Appropriate use of HTML inputs (e.g.  email, phone, etc) to trigger corresponding on-screen keyboards

Code Base Checks

  All code is checked into SVN or other  source code repository
  Unused sections of code are removed
  Code is commented where appropriate
  Client-side code is free of any  references to development and staging environments, URLs, or other development  settings (e.g. dev Facebook application IDs)
  Any environmental defaults reference  production.
  Any dependency definitions use exact  versions.

Code Review Tools

  Markup: DOM Monster bookmarklet
  Markup: Diagnose Chrome Extension
  Markup: W3C HTML validator
  CSS: W3C CSS validator
  Performance: YSlow
  Performance: PageSpeed
  JavaScript: JSLint/JSHint
  Accessibility: SortSite
  Accessibility: JAWS/NVDA/VoiceOver
  Accessibility: CynthiaSays