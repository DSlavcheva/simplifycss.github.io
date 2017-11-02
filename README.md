<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta content="IE=edge" http-equiv="X-UA-Compatible">
    <meta content="width=device-width, initial-scale=1" name="viewport">
    <link href="css/styles.css" rel="stylesheet" type="text/css">
    <link href="css/docs.css" rel="stylesheet" type="text/css">
  </head>
  <body>
    <div id="layout">
      <div id="sidenav">
        <div id="side-logo">
          <a href="./home.html"><img src="./img/logo-sidebar.jpg"></a>
        </div>
        <nav class="navigation" id="mainNav">
          <div class="nav-header">
            Getting started
          </div>
          <ul>
            <li>
              <a class="navigation__link" href="#section-what-is">What is Simplify?</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-installation">Installation</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-browser-support">Browser Support</a>
            </li>
          </ul>
          <div class="nav-header">
            Elements
          </div>
          <ul>
            <li>
              <a class="navigation__link" href="#section-typography">Typography</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-buttons">Buttons</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-code">Code</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-forms">Forms</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-tables">Tables</a>
            </li>
          </ul>
          <div class="nav-header">
            Layout
          </div>
          <ul>
            <li>
              <a class="navigation__link" href="#section-breakpoints">Breakpoints</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-containers">Containers</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-grid">Grid</a>
            </li>
          </ul>
          <div class="nav-header">
            Components
          </div>
          <ul>
            <li>
              <a class="navigation__link" href="#section-accordion">Accordion</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-breadcrumbs">Breadcrumbs</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-nav">Nav</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-tabs">Tabs</a>
            </li>
          </ul>
          <!---<div class="nav-header">
            Angular
          </div>
          <ul>
            <li>
              <a class="navigation__link" href="#section-carousel">Carousel</a>
            </li>
            <li>
              <a class="navigation__link" href="#section-scrollspy">Scrollspy</a>
            </li>
          </ul> -->
        </nav>
      </div>
      <div id="content">
        <div class="sections container">
          <h3>
            Getting started
          </h3>
          <div class="page-section" id="section-what-is">
            <h4 class="special">
              What is Simplify?
            </h4>
            <p>
              Simplify is a minimal CSS framework written with SASS and Compass. It is ideal for graphic designers who wish to implement a website design themselves and do so in a simple, yet effective manner ( meaning without any front-end devs getting in the way :)
            </p>
            <p>
              The framework contains basic styling rules for elements, a flexbox-based grid system and a few must-have CSS-only components, which can be easily customized to the designer's preference. To reset browser styles, <code>normalize.css</code> is included in the framework file.
            </p>
            <p>
              Web developers that wish to create their own website styles without having to ask a designer for every heading and pixel could also benefit from Simplify. That's why it goes a step further by providing a few (but hopefully growing in numbers!) Angular 2+ components to help style web apps effortlessly.
            </p>
          </div>
          <p></p>
          <div class="page-section" id="section-installation">
            <h4 class="special">
              Installation
            </h4>
            <p>
              It is strongly advised to have your own CSS file for any changes that you need to make on the styles instead of editing the <code>simplify.css</code> file directly. If you chose to call it <code>my-style.css</code> then include it in your HTML file like this
            </p>
            <pre><code> &lt;link rel="stylesheet" href="<b>my-style.css</b>" type="text/css&gt; </code></pre>
            <p></p>
            <h5 class="special">
              Include from CDN
            </h5>
            <p>
              You can just link the CDN in your html document and you're good to go.
            </p>
            <pre><code> &lt;link rel="stylesheet" href="https://unpkg.com/simplify.min.css" /&gt; </code></pre>
            <h5 class="special">
              Install with npm
            </h5>
            <p>
              Alternatively, you can get the whole package via npm
            </p>
            <pre><code>$ npm install simplify </code></pre>
            <h5 class="special">
              Download
            </h5>
            <p>
              You can download the minified css file to include in your projects or get the whole .zip package from Github.
            </p><a class="button" href="#">Minified css</a> <a class="button" href="#">Package .zip</a>
            <p></p>
            <h5 class="special">
              Customize
            </h5>
            <p>
              To customize the Simplify core and compile your own project, you'd need to get <a href="http://sass-lang.com/" target="_blank">SASS</a> and <a href="http://compass-style.org/" target="_blank">Compass</a> in addition to the master package from above.
            </p>
          </div>
          <div class="page-section" id="section-browser-support">
            <h4 class="special">
              Browser Support
            </h4>
            <p>
              Simplify is built with modern browsers in mind, however the CSS is prefixed for the last two versions of commonly used browsers.
            </p>
          </div>
          <h3>
            Elements
          </h3>
          <div class="page-section" id="section-typography">
            <h4 class="special">
              Typography
            </h4>
            <p>
              The beautiful font that was used to build this website is called Poppins by Jonny Pinhorn and provided by Google Fonts. To use it in your own website add the following in your HTML <code>head</code>.
            </p>
            <pre><code>&lt;link href="https://fonts.googleapis.com/css?family=Poppins:300,400,700" rel="stylesheet"&gt;</code></pre>
            <p>
              You can also download and add the font files to their own folder called <code>poppins</code> in the <code>/fonts</code> sub-direcory of your main project.
            </p>
            <p>
              Headings use the semantic classes <code>h1</code> through <code>h6</code>. REMs are used to set the font-size relative to <code>16px</code> root size as well as line height relative to a <code>24px</code> base.
            </p>
            <p></p>
            <h1>
              Heading H1 <code>46px</code>
            </h1>
            <h2>
              Heading H2 <code>36px</code>
            </h2>
            <h3>
              Heading H3 <code>28px</code>
            </h3>
            <h4>
              Heading H4 <code>22px</code>
            </h4>
            <h5>
              Heading H5 <code>18px</code>
            </h5>
            <h6>
              Heading H6 <code>16px</code>
            </h6>
            <pre><code>&lt;h1&gt;Heading&lt;/h1&gt;     &lt;!-- font-size: 2.875rem/46px line-height: 4.5rem/72px --&gt;
&lt;h2&gt;Heading&lt;/h2&gt;    &lt;!-- font-size: 2.25rem/36px line-height: 3rem/48px --&gt;
&lt;h3&gt;Heading&lt;/h3&gt;    &lt;!-- font-size: 1.75rem/28px line-height: 3rem/48px --&gt;
&lt;h4&gt;Heading&lt;/h4&gt;    &lt;!-- font-size: 1.375rem/22px line-height: 3rem/48px --&gt;
&lt;h5&gt;Heading&lt;/h5&gt;    &lt;!-- font-size: 1.125rem/18px line-height: 1.5rem/24px --&gt;
&lt;h6&gt;Heading&lt;/h6&gt;    &lt;!-- font-size: 1.5rem line/16px line-height: 1.5rem/24px --&gt;</code></pre>
          </div>
          <div class="page-section" id="section-buttons">
            <h4 class="special">
              Buttons
            </h4>
            <p>
              Simplify covers three most basic styles of buttons with the default <code>button</code> element having a flat-color background and hover effect. Additionally, the <code>.button-outline</code> class provides a button with just an outline and the <code>.button-clear</code> class gives us a clear button. Pretty self-explanatory, huh?
            </p><a class="button" href="#">Default Button</a> <button class="button button-outline">Outlined Button</button> <input class="button button-clear" type="submit" value="Clear Button">
            <pre><code>&lt;!-- Default Button --&gt;
&lt;a class="button" href="#"&gtDefault Button&lt;/a&gt;

&lt;!-- Outlined Button --&gt;
&lt;button class="button button-outline"&gt;Outlined Button&lt;/button&gt;

&lt;!-- Clear Button --&gt;
&lt;input class="button button-clear" value="Clear Button" type="submit"&gt;</code></pre>
          </div>
          <div class="page-section" id="section-code">
            <h4 class="special">
              Code
            </h4>
            <p>
              Making text appear like computer code just like the examples on this page is easy. Wrap any word in a <code>&lt;code&gt;</code> tag to make it appear as inline code. To show beautiful blocks of code, add a <code>&lt;pre&gt;</code> tag around the <code>&lt;code&gt;</code>.
            </p>
            <pre><code>&lt;pre&gt;&lt;code&gt;
.style {
  color: #00000;
}
&lt;/code&gt;&lt;/pre&gt;</code></pre>
            <p></p>
          </div>
          <div class="page-section" id="section-forms">
            <h4 class="special">
              Forms
            </h4>
            <p>
              Here's how a form looks like by default when using Simplify with the code shown below. Neat, right?
            </p>
            <form>
              <fieldset>
                <label for="nameField">Name</label> <input id="nameField" placeholder="Jonh Doe" type="text"> <label for="ageRangeField">Age Range</label> <select id="ageRangeField">
                  <option value="0-13">
                    0-13
                  </option>
                  <option value="14-17">
                    14-17
                  </option>
                  <option value="18-23">
                    18-23
                  </option>
                  <option value="24+">
                    24+
                  </option>
                </select> <label for="commentField">Comment</label> 
                <textarea id="commentField" placeholder="Lorem ipsum dolor"></textarea>
                <div class="float-right">
                  <input id="confirmField" type="checkbox"> <label class="label-inline" for="confirmField">I Agree</label>
                </div><input class="button-primary" type="submit" value="Send">
              </fieldset>
            </form>
            <pre><code>&lt;form&gt;
  &lt;fieldset&gt;
     &lt;label for="nameField"&gt;Name&lt;/label&gt;
     &lt;input placeholder="John Doe" id="nameField" type="text"&gt;
     &lt;label for="ageRangeField"&gt;Age Range&lt;/label&gt;
     &lt;select id="ageRangeField"&gt;
        &lt;option value="0-13"&gt;0-13&lt;/option&gt;
        &lt;option value="14-17"&gt;14-17&lt;/option&gt;
        &lt;option value="18-23"&gt;18-23&lt;/option&gt;
        &lt;option value="24+"&gt;24+&lt;/option&gt;
     &lt;/select&gt;
     &lt;label for="commentField"&gt;Comment&lt;/label&gt;
     &lt;textarea placeholder="Lorem ipsum dolor" id="commentField"&gt;&lt;/textarea&gt;
     &lt;div class="float-right"&gt;
        &lt;input id="confirmField" type="checkbox"&gt;
        &lt;label class="label-inline" for="confirmField"&gt;I Agree&lt;/label&gt;
       &lt;/div&gt;
     &lt;input class="button-primary" value="Send" type="submit"&gt;
  &lt;/fieldset&gt;
&lt;/form&gt;</code></pre>
            <p></p>
          </div>
          <div class="page-section" id="section-tables">
            <h4 class="special">
              Tables
            </h4>
            <p>
              Data tables can be a pain when aiming for mobile devices, so Simplify provides awesome responsive tables made using the nifty <a href="https://css-tricks.com/responsive-data-tables/">No More Tables</a> principle. Resize your browser screen to see the magic happen.
            </p>fdx
            <table>
              <caption>
                Table Caption
              </caption>
              <thead>
                <tr>
                  <th scope="col">
                    Table head
                  </th>
                  <th scope="col">
                    Table head
                  </th>
                  <th scope="col">
                    Table head
                  </th>
                  <th scope="col">
                    Table head
                  </th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td data-title="Table head">
                    Lorem ipsum
                  </td>
                  <td data-title="Table head">
                    01/01/1990
                  </td>
                  <td data-title="Table head">
                    10,000
                  </td>
                  <td data-title="Table head">
                    01/01/1990 - 01/31/1990
                  </td>
                </tr>
                <tr>
                  <td data-title="Table head">
                    Lorem ipsum
                  </td>
                  <td data-title="Table head">
                    01/01/1990
                  </td>
                  <td data-title="Table head">
                    10,000
                  </td>
                  <td data-title="Table head">
                    01/01/1990 - 01/31/1990
                  </td>
                </tr>
                <tr>
                  <td data-title="Table head">
                    Lorem ipsum
                  </td>
                  <td data-title="Table head">
                    01/01/1990
                  </td>
                  <td data-title="Table head">
                    $10,000
                  </td>
                  <td data-title="Table head">
                    01/01/1990 - 01/31/1990
                  </td>
                </tr>
                <tr>
                  <td data-title="Table head">
                    Lorem ipsum
                  </td>
                  <td data-title="Table head">
                    01/01/1990
                  </td>
                  <td data-title="Table head">
                    10,000
                  </td>
                  <td data-title="Table head">
                    01/01/1990 - 01/31/1990
                  </td>
                </tr>
              </tbody>
            </table>
            <pre><code>&lt;table&gt;
  &lt;caption&gt;Table Caption&lt;/caption&gt;
  &lt;thead&gt;
   &lt;tr&gt;
    &lt;th scope="col"&gt;Table head&lt;/th&gt;
    &lt;th scope="col"&gt;Table head&lt;/th&gt;
    &lt;th scope="col"&gt;Table head&lt;/th&gt;
    &lt;th scope="col"&gt;Table head&lt;/th&gt;
   &lt;/tr&gt;
  &lt;/thead&gt;
  &lt;tbody&gt;
   &lt;tr&gt;
    &lt;td data-title="Table head"&gt;Lorem ipsum&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990&lt;/td&gt;
    &lt;td data-title="Table head"&gt;10,000&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990 - 01/31/1990&lt;/td&gt;
   &lt;/tr&gt;
   &lt;tr&gt;
    &lt;td data-title="Table head"&gt;Lorem ipsum&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990&lt;/td&gt;
    &lt;td data-title="Table head"&gt;10,000&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990 - 01/31/1990&lt;/td&gt;
   &lt;/tr&gt;
   &lt;tr&gt;
    &lt;td data-title="Table head"&gt;Lorem ipsum&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990&lt;/td&gt;
    &lt;td data-title="Table head"&gt;$10,000&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990 - 01/31/1990&lt;/td&gt;
   &lt;/tr&gt;
   &lt;tr&gt;
    &lt;td data-title="Table head"&gt;Lorem ipsum&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990&lt;/td&gt;
    &lt;td data-title="Table head"&gt;10,000&lt;/td&gt;
    &lt;td data-title="Table head"&gt;01/01/1990 - 01/31/1990&lt;/td&gt;
   &lt;/tr&gt;
  &lt;/tbody&gt;
 &lt;/table&gt;
 &lt;/div&gt;</code></pre>
            <p></p>
          </div>
          <h3>
            Layout
          </h3>
          <div class="page-section" id="section-breakpoints">
            <h4 class="special">
              Breakpoints
            </h4>
            <p>
              To make your life a lot easier, by default Simplify utilizes a single breakpoint at <code>768px</code> for its responsive elements. This way you needn't worry about flooding your HTML markup with non-semantic classes (like <code>col-xs</code> <code>col-md</code> <code>col-lg</code> etc.) while still rocking a pretty responsive layout. Also, the framework aims at the mobile-first approach to serve content faster for those low bandwidth mobile devices.
            </p>
          </div>
          <div class="page-section" id="section-containers">
            <h4 class="special">
              Containers
            </h4>
            <p>
              To lay things nicely on your page and use the grid, you need to use the <code>container</code> class. By default, the container takes up 80% of the page, has a max-width set 1280px and is centered to the viewport.
            </p>
            <pre><code>&lt;div class="container"&gt;
    &lt;!-- 
    Container width: 80% 
    max-width: 80 rem (1280px)
    --&gt;
&lt;/div&gt;</code></pre>
            <p></p>
          </div>
          <div class="page-section" id="section-grid">
            <h4 class="special">
              Grid
            </h4>
            <p>
              The grid is the heart and soul of any CSS framework, so it should be easy to use, simple and responsive. Simplify is made using the CSS Flexible Box layout module (Flexbox for short) to cover all three of those requirements.
            </p>
            <p>
              You need to use a <code>container</code> class as mentioned above, then wrap some <code>columns</code> inside a <code>row</code> class. *Bam!*, you're done! And your content will scale responsively along - resize your browser window to check it out.
            </p>
            <div class="container example">
              <div class="row">
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
              </div>
            </div>
            <pre><code>&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="column"&gt;&lt;/div&gt;
    &lt;div class="column"&gt;&lt;/div&gt;
    &lt;div class="column"&gt;&lt;/div&gt;
    &lt;div class="column"&gt;&lt;/div&gt;
  &lt;/div&gt;      
&lt;/div&gt;</code></pre>
            <p>
              You can add as many columns as you'd like and by default they will distribute evenly across the grid, however using no more than the good-ol' 12 is advisable for best results.
            </p>
            <p>
              Offsetting your columns by a desired percent is also possible by appending the <code>column-offset-NUMBER</code> class, where <code>NUMBER</code> can be one of <code>10, 20, 25, 33, 40, 50, 66, 75, 80, 90</code>.
            </p>
            <div class="container example">
              <div class="row">
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column column-50 column-offset-50">
                  <span class="grid-visible">.column</span>
                </div>
              </div>
            </div>
            <pre><code>&lt;div class="container"&gt;
  &lt;div class="row"&gt;
    &lt;div class="column"&gt;&lt;/div&gt;
    &lt;div class="column column- column-offset-50"&gt;&lt;/div&gt;          
  &lt;/div&gt;      
&lt;/div&gt;</code></pre>
            <p>
              How much space should a column take up relatively to a percentage can be set manually by using the <code>coulmn-NUMBER</code> class the same way.
            </p>
            <div class="container example">
              <div class="row">
                <div class="column column-10">
                  <span class="grid-visible">10%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-20">
                  <span class="grid-visible">20%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-25">
                  <span class="grid-visible">25%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-33">
                  <span class="grid-visible">33%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-40">
                  <span class="grid-visible">40%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-50">
                  <span class="grid-visible">50%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-60">
                  <span class="grid-visible">60%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-67">
                  <span class="grid-visible">67%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-75">
                  <span class="grid-visible">75%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-80">
                  <span class="grid-visible">80%</span>
                </div>
              </div>
              <div class="row">
                <div class="column column-90">
                  <span class="grid-visible">90%</span>
                </div>
              </div>
              <div class="row">
                <div class="column">
                  <span class="grid-visible">100%</span>
                </div>
              </div>
            </div>
            <pre><code>&lt;div class="container"&gt;
 &lt;div class="row"&gt;
  &lt;div class="column column-10"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-20"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-25"
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-33"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-40"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-50"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-60"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-67"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-75"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-80"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column column-90"&gt;&lt;/div&gt;
 &lt;/div&gt;
 
 &lt;div class="row"&gt;
  &lt;div class="column"&gt;&lt;/div&gt;
 &lt;/div&gt;
&lt;/div&gt;</code></pre>
            <p></p>
            <p>
              If you want a row to have no padding, you can use the <code>row-no-padding</code> class.
            </p>
            <div class="container example">
              <div class="row row-no-padding">
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
                <div class="column">
                  <span class="grid-visible">.column</span>
                </div>
              </div>
            </div>
            <pre><code>&lt;div class="container example"&gt;
 &lt;div class="row row-no-padding"&gt;
  &lt;div class="column"&gt;&lt;/div&gt;
  &lt;div class="column"&gt;&lt;/div&gt;
  &lt;div class="column"&gt;&lt;/div&gt;
  &lt;div class="column"&gt;&lt;/div&gt;
 &lt;/div&gt;
&lt;/div&gt;</code></pre>
            <p></p>
          </div>
          <h3>
            Components
          </h3>
          <div class="page-section" id="section-accordion">
            <h4 class="special">
              Accordion
            </h4>
            <p>
              Accordions are used when you want to toggle between hiding and showing some content. The separate parts of an accordion are called <code>panels</code>.
            </p>
            <div class="panel">
              <input id="panel-one" name="accordion" type="checkbox"> <label for="panel-one">Label One</label>
              <div class="panel-content">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur, architecto, explicabo perferendis nostrum, maxime impedit atque odit sunt pariatur illo obcaecati soluta molestias iure facere dolorum adipisci eum? Saepe, itaque.
                </p>
              </div>
            </div>
            <div class="panel">
              <input id="panel-two" name="accordion" type="checkbox"> <label for="panel-two">Label Two</label>
              <div class="panel-content">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur, architecto, explicabo perferendis nostrum, maxime impedit atque odit sunt pariatur illo obcaecati soluta molestias iure facere dolorum adipisci eum? Saepe, itaque.
                </p>
              </div>
            </div>
            <div class="panel">
              <input id="panel-three" name="accordion" type="checkbox"> <label for="panel-three">Label Three</label>
              <div class="panel-content">
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur, architecto, explicabo perferendis nostrum, maxime impedit atque odit sunt pariatur illo obcaecati soluta molestias iure facere dolorum adipisci eum? Saepe, itaque.
                </p>
              </div>
            </div>
            <pre><code>&lt;div class="panel"&gt;
  &lt;input id="panel-one" type="checkbox" name="accordion"&gt;
  &lt;label for="panel-one"&gt;Label One&lt;/label&gt;
  &lt;div class="panel-content"&gt;
   &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur, architecto, explicabo perferendis nostrum, maxime impedit atque odit sunt pariatur illo obcaecati soluta molestias iure facere dolorum adipisci eum? Saepe, itaque.&lt;/p&gt;
  &lt;/div&gt;
 &lt;/div&gt;

 &lt;div class="panel"&gt;
  &lt;input id="panel-two" type="checkbox" name="accordion"&gt;
  &lt;label for="panel-two"&gt;Label Two&lt;/label&gt;
  &lt;div class="panel-content"&gt;
   &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur, architecto, explicabo perferendis nostrum, maxime impedit atque odit sunt pariatur illo obcaecati soluta molestias iure facere dolorum adipisci eum? Saepe, itaque.&lt;/p&gt;
  &lt;/div&gt;
  
  &lt;div class="panel"&gt;
  &lt;input id="panel-three" type="checkbox" name="accordion"&gt;
  &lt;label for="panel-three"&gt;Label Two&lt;/label&gt;
  &lt;div class="panel-content"&gt;
   &lt;p&gt;Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tenetur, architecto, explicabo perferendis nostrum, maxime impedit atque odit sunt pariatur illo obcaecati soluta molestias iure facere dolorum adipisci eum? Saepe, itaque.&lt;/p&gt;
  &lt;/div&gt;
&lt;/div&gt;</code></pre>
            <p></p>
          </div>
          <div class="page-section" id="section-breadcrumbs">
            <h4 class="special">
              Breadcrumbs
            </h4>
            <p>
              Breadcrumbs are a secondary type of navigation that marks the current position of the user in a website or a web app. They're actually called so because of the Hansel and Gretel fairy tale you're most certainly familiar with :)
            </p>
            <div class="breadcrumb clearfix" id="breadcrumb">
              <ul>
                <li class="breadcrumb-link">
                  <a href="#">Overview</a>
                </li>
                <li class="breadcrumb-link">
                  <a href="#">Category Level 1</a>
                </li>
                <li class="breadcrumb-link">
                  <a href="#">Category Level 2</a>
                </li>
                <li class="breadcrumb--active">Active Level
                </li>
              </ul>
            </div>
            <p></p>
            <p></p>
            <pre><code>&lt;div id="breadcrumb" class="breadcrumb"&gt;
 &lt;ul&gt;
   &lt;li class="breadcrumb-link"&gt;&lt;a href="#"&gt;Overview&lt;/a&gt;&lt;/li&gt;
   &lt;li class="breadcrumb-link"&gt;&lt;a href="#"&gt;Category Level 1&lt;/a&gt;&lt;/li&gt;
   &lt;li class="breadcrumb-link"&gt;&lt;a href="#"&gt;Category Level 2&lt;/li&gt;
   &lt;li class="breadcrumb--active"&gt;Active Level&lt;/a&gt;&lt;/li&gt;
 &lt;/ul&gt;            
&lt;/div&gt;</code></pre>
            <p></p>
          </div>
          <div class="page-section" id="section-nav">
            <h4 class="special">
              Nav
            </h4>
            <p>
              Simplify's nav uses the <a href="https://css-tricks.com/the-checkbox-hack/">checkbox hack</a> to provide you with a pure CSS responsive navbar. Resize the browser window and you'll see it in action.
            </p>
            <div class="container example">
              <nav class="nav-menu menu-left" id="test-nav">
                <div class="nav-logo logo-right">
                  <a href="#">LOGO</a>
                </div><label for="tm" id="toggle-menu">Menu <span class="drop-icon">&#10093;</span></label> <input id="tm" type="checkbox">
                <ul class="main-menu clearfix">
                  <li>
                    <a href="#">Item 1</a>
                  </li>
                  <li>
                    <a href="#">Item 2 <span class="drop-icon">&#10093;</span> <label class="drop-icon" for="sm1" title="Toggle Drop-down">&#10093;</label></a> <input id="sm1" type="checkbox">
                    <ul class="sub-menu">
                      <li>
                        <a href="#">Item 2.1</a>
                      </li>
                      <li>
                        <a href="#">Item 2.2 <span class="drop-icon">&#10093;</span> <label class="drop-icon" for="sm2" title="Toggle Drop-down">&#10093;</label></a> <input id="sm2" type="checkbox">
                        <ul class="sub-menu">
                          <li>
                            <a href="#">Item 2.2.1</a>
                          </li>
                          <li>
                            <a href="#">Item 2.2.2</a>
                          </li>
                          <li>
                            <a href="#">Item 2.2.3</a>
                          </li>
                        </ul>
                      </li>
                      <li>
                        <a href="#">Item 2.3</a>
                      </li>
                    </ul>
                  </li>
                  <li>
                    <a href="#">Item 3</a>
                  </li>
                </ul>
              </nav>
            </div>
            <pre><code><b>&lt;nav class="nav-menu menu-left"&gt;</b>
  <b>&lt;div class="nav-logo logo-right"&gt;</b>
  &lt;a href="#"&gt;LOGO&lt;/a&gt;&lt;/div&gt;
  <b>&lt;label for="tm" id="toggle-menu"&gt;</b>Menu<b>
    &lt;span class="drop-icon"&gt;&#10093;&lt;/span&gt;&lt;/label&gt;</b> 
  <b>&lt;input id="tm" type="checkbox"&gt;</b>
  <b>&lt;ul class="main-menu clearfix"&gt;</b>
  &lt;li&gt;&lt;a href="#"&gt;Item 1&lt;/a&gt;&lt;/li&gt;
  &lt;li&gt;
   &lt;a href="#"&gt;Item 2 
     <b>&lt;span class="drop-icon"&gt;&#10093;&lt;/span&gt; </b>
   <b>&lt;label class="drop-icon" for="sm1"</b> title="Toggle Drop-down"&gt;&#10093;
   &lt;/label&gt;&lt;/a&gt;
   <b>&lt;input id="sm1" type="checkbox"&gt;</b>
   <b>&lt;ul class="sub-menu"&gt;</b>
    &lt;li&gt;&lt;a href="#"&gt;Item 2.1&lt;/a&gt;&lt;/li&gt;
    &lt;li&gt;
     &lt;a href="#"&gt;Item 2.2 
     <b>&lt;span class="drop-icon"&gt;&#10093;&lt;/span&gt; </b>
     <b>&lt;label class="drop-icon" for="sm2"</b> title="Toggle Drop-down"&gt;&#10093;
     &lt;/label&gt;&lt;/a&gt; 
     <b>&lt;input id="sm2" type="checkbox"&gt;</b>
     <b>&lt;ul class="sub-menu"&gt;</b>
      &lt;li&gt;&lt;a href="#"&gt;Item 2.2.1&lt;/a&gt;&lt;/li&gt;
      &lt;li&gt;&lt;a href="#"&gt;Item 2.2.2&lt;/a&gt;&lt;/li&gt;
      &lt;li&gt;&lt;a href="#"&gt;Item 2.2.3&lt;/a&gt;&lt;/li&gt;
     &lt;/ul&gt;
    &lt;/li&gt;
    &lt;li&gt;&lt;a href="#"&gt;Item 2.3&lt;/a&gt;&lt;/li&gt;
   &lt;/ul&gt;
  &lt;/li&gt;
  &lt;li&gt;&lt;a href="#"&gt;Item 3&lt;/a&gt;&lt;/li&gt;
  &lt;/ul&gt;
&lt;/nav&gt;</code></pre>
            <p>
              To get a navigation bar you need a <code>nav</code> element with a <code>class="nav-menu"</code>.
            </p>
            <p>
              The opening toggle for the mobile version of the menu requires adding the <code>&lt;label for="tm" id="toggle-menu"&gt;</code> along with the <code>&lt;input type="checkbox" id="tm"&gt;</code>. The <code>&amp;#10093;</code> code inside the <code>&lt;span class="drop-icon"&gt;</code> is used for the arrow &#10093; and is transformed with CSS when a down-arrow is needed.
            </p>
            <p></p>
            <p>
              You can define a right or left alignment for the navbar with the <code>menu-right</code> and <code>menu-left</code> classes as shown above.
            </p>
            <p>
              If you want to put a logo on your navigation then add the <code>&lt;div class="nav-logo"&gt;</code> and set its position with the <code>logo-right</code> and <code>logo-left</code> classes. Appending the <code>fixed</code> class to the <code>nav</code> element makes sure the navigation always sticks to the top of the page.
            </p>
            <p>
              Dropdowns are achieved by adding <code>&lt;ul class="sub-menu"&gt;</code> and the respective <code>checkbox</code> and <code>label</code> elements.
            </p>
          </div>
          <div class="page-section" id="section-tabs">
            <h4 class="special">
              Tabs
            </h4>
            <p>
              Tabs are perfect when you're aiming for that tidy one-pager look and want to keep your content organised and clean-looking. Again, responsiveness is a must and Simplify has got you covered.
            </p>
            <div class="tab-wrap">
              <input checked class="tab" id="tab1" name="tabGroup" type="radio"> <label for="tab1">Section One</label> <input class="tab" id="tab2" name="tabGroup" type="radio"> <label for="tab2">Section Two</label> <input class="tab" id="tab3" name="tabGroup" type="radio"> <label for="tab3">Section Three</label> <input class="tab" id="tab4" name="tabGroup" type="radio"> <label for="tab4">Section Four</label>
              <div class="tab__content">
                <h3>
                  Section One
                </h3>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
              </div>
              <div class="tab__content">
                <h3>
                  Section Two
                </h3>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
                <p>
                  In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Morbi mattis ullamcorper velit. Pellentesque posuere. Etiam ut purus mattis mauris sodales aliquam. Praesent nec nisl a purus blandit viverra.
                </p>
              </div>
              <div class="tab__content">
                <h3>
                  Section Three
                </h3>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
                <p>
                  In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Morbi mattis ullamcorper velit. Pellentesque posuere. Etiam ut purus mattis mauris sodales aliquam. Praesent nec nisl a purus blandit viverra.
                </p>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
                <p>
                  In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Morbi mattis ullamcorper velit. Pellentesque posuere. Etiam ut purus mattis mauris sodales aliquam. Praesent nec nisl a purus blandit viverra.
                </p>
              </div>
              <div class="tab__content">
                <h3>
                  Section Four
                </h3>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
                </p>
              </div>
            </div>
            <pre><code><b>&lt;div class="tab-wrap"&gt;
    &lt;input checked class="tab" id="tab1" name="tabGroup" type="radio"&gt;
    &lt;label for="tab1"&gt;Section One&lt;/label&gt;</b>
    
    &lt;input class="tab" id="tab2" name="tabGroup" type="radio"&gt;
    &lt;label for="tab2"&gt;Section Two&lt;/label&gt;
    
    &lt;input class="tab" id="tab3" name="tabGroup" type="radio"&gt;
    &lt;label for="tab3"&gt;Section Three&lt;/label&gt;
    
    &lt;input class="tab" id="tab4" name="tabGroup" type="radio"&gt;
    &lt;label for="tab4"&gt;Section Four&lt;/label&gt;
    
    <b>&lt;div class="tab__content"&gt;</b>
        &lt;h3&gt;Section One&lt;/h3&gt;
        &lt;p&gt;Content goes here&lt;/p&gt;
    &lt;/div&gt;
    <b>&lt;div class="tab__content"&gt;</b>
        &lt;h3&gt;Section Two&lt;/h3&gt;
        &lt;p&gt;Content goes here&lt;/p&gt;
    &lt;/div&gt;
<b> &lt;div class="tab__content"&gt;</b>
        &lt;h3&gt;Section Three&lt;/h3&gt;
        &lt;p&gt;Content goes here&lt;/p&gt;
    &lt;/div&gt;
<b> &lt;div class="tab__content"&gt;</b>
        &lt;h3&gt;Section Four&lt;/h3&gt;
        &lt;p&gt;Content goes here&lt;/p&gt;
    &lt;/div&gt;
&lt;/div&gt;</code></pre>
            <p>
              Let's take a look at the syntax. You wrap the whole thing in a <code>&lt;div class="tab-wrap"&gt;</code> and for the contents of each tab you add a <code>&lt;div class="tab__content"&gt;</code>.
            </p>
            <p>
              For each tab you add a <code>radio</code> with the <code>tab</code> clss and a corresponding <code>label</code> as shown. The <code>checked</code> class marks the current open tab.
            </p>
            <p>
              Now, depending on the number of tabs you have, you need to modify some CSS code for showing the tabs content. If you had 2 tabs, you'd have the following selectors
            </p>
            <pre><code>.tab:checked:nth-of-type(1)~.tab__content:nth-of-type(1),
.tab:checked:nth-of-type(2)~.tab__content:nth-of-type(2)</code></pre>
            <p>
              Since making the changes to your own <code>custom-style.css</code> file is strongly advised, just copy-paste and adjust the whole code block with your selector like that
            </p>
            <pre><code><b>.tab:checked:nth-of-type(1)~.tab__content:nth-of-type(1),
.tab:checked:nth-of-type(2)~.tab__content:nth-of-type(2)</b> {
    opacity: 1;
    position: relative;
    top: 0;
    -webkit-transform: translateY(0);
    transform: translateY(0);
    -webkit-transition: .5s opacity ease-in, .2s transform ease;
    -webkit-transition: .5s opacity ease-in, .2s -webkit-transform ease;
    transition: .5s opacity ease-in, .2s -webkit-transform ease;
    transition: .5s opacity ease-in, .2s transform ease;
    transition: .5s opacity ease-in, .2s transform ease, .2s -webkit-transform ease;
    z-index: 1;
}</code></pre>
          </div>
          <h3>
            Angular
          </h3>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis et nisi a lorem tincidunt mattis vitae eu augue. Donec cursus ex sit amet neque volutpat feugiat. Quisque nisl purus, dignissim sit amet purus at, volutpat tincidunt nunc. Praesent dapibus faucibus neque eget sagittis. Proin ipsum mauris, tincidunt et ante in, mattis ornare tellus. Cras ac lobortis turpis. Nam consequat, justo quis placerat rutrum, magna velit pretium magna, sit amet congue diam turpis sed erat. In lacinia lorem id orci gravida, eu dapibus ipsum molestie. Duis sagittis leo sit amet diam suscipit, a pellentesque sem pharetra. Donec a lacinia odio. Mauris nec tempus metus, a pellentesque diam. In fringilla id sapien in sagittis. Suspendisse dolor nunc, pretium vitae faucibus ac, mattis fringilla ipsum. Vivamus ultricies enim ac orci gravida, vel semper turpis aliquet. In semper at odio quis mattis. In auctor pretium quam, at euismod mi dapibus ac. Sed eget turpis vestibulum, pharetra urna vitae, eleifend magna. Pellentesque ultrices magna eu porttitor suscipit. Aliquam in sollicitudin dui. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Aenean pharetra posuere diam. Integer at laoreet sem. Cras libero justo, cursus quis lobortis et, convallis non felis. Nullam ut erat vel elit posuere vulputate non vel massa. Nulla sed libero sed urna mattis efficitur. In dapibus, mauris eu vehicula dignissim, eros diam posuere est, vitae tincidunt felis sem quis ante. Donec sed metus posuere, molestie lacus eu, facilisis diam. Fusce quis vulputate augue, vel mollis dolor. Vestibulum maximus varius risus, eu pellentesque orci rutrum non. Ut fermentum nisl ac venenatis consectetur. Etiam vel leo ac nisi laoreet cursus. Sed ornare massa at mauris aliquam molestie. Proin mattis venenatis libero vehicula placerat. Fusce at libero cursus, fermentum eros sit amet, maximus elit. Donec et elit sed magna placerat accumsan sed ac elit. Sed at mauris et leo cursus ornare ut vel turpis. Cras in tristique lorem. Vivamus non vestibulum est. Quisque in varius est. Donec volutpat non mauris at facilisis. Proin rhoncus pellentesque arcu sed ultricies. Nullam ultrices consectetur massa, in rutrum orci auctor vel. Suspendisse iaculis, libero et faucibus ullamcorper, nisl erat ornare ipsum, vitae finibus tortor dui eget tellus. Etiam lectus urna, congue at libero vitae, tristique consectetur ligula. Nulla eleifend ac massa sed laoreet. Quisque erat elit, fringilla at dolor id, congue sollicitudin sapien. Praesent congue pulvinar elit vitae auctor. Suspendisse commodo dolor eu nisl euismod tempus. Donec molestie egestas lectus in interdum. Duis convallis placerat quam, at consequat ex malesuada ut. Donec suscipit egestas finibus. Mauris ac malesuada felis, non lacinia velit. Donec vestibulum lacus massa, ac consequat nisl gravida nec. Sed non dui vel nisl cursus consequat. Sed ac lacinia mauris. Ut non velit pretium lectus facilisis varius.
          <div class="page-section" id="section-carousel">
            <h4 class="special">
              Carousel
            </h4>
          </div>
          <div class="page-section" id="section-scrollspy">
            <h4 class="special">
              Scrollspy
            </h4>
          </div>
        </div>
        <footer>
          <div class="container">
            Designed and built by Denitsa Slavcheva. Released under the <a href="https://github.com/simplifycss/simplifycss.github.io/blob/master/LICENSE">MIT license</a>.
          </div>
        </footer>
      </div>
    </div>
  </body>
</html>
