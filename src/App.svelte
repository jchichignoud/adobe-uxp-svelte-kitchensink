<script>

</script>

<style>

</style>

<div class="wrapper">
    <div class="sp-tabs">
      <div class="sp-tab selected" id="sp-spectrum-typography-tab"><sp-label>Spectrum Typography</sp-label></div>
      <div class="sp-tab" id="sp-spectrum-widgets-tab"><sp-label>Spectrum Widgets</sp-label></div>
      <div class="sp-tab" id="sp-native-tab"><sp-label>Native</sp-label></div>
      <div class="sp-tab" id="sp-html-tab"><sp-label>HTML</sp-label></div>
      <div class="sp-tab" id="sp-events-tab"><sp-label>Events</sp-label></div>
    </div>
    <div class="sp-tab-page visible" id="sp-spectrum-typography-tab-page">
      <div class="group"><sp-label>Heading</sp-label>
        <sp-detail>NORMAL HEADING</sp-detail>
        <sp-heading>Heading</sp-heading>
        <sp-detail>HEADING SIZES</sp-detail>
        <sp-heading size="XXXL">Heading XXXL</sp-heading>
        <sp-heading size="XXL">Heading XXL</sp-heading>
        <sp-heading size="XL">Heading XL</sp-heading>
        <sp-heading size="L">Heading L</sp-heading>
        <sp-heading size="M">Heading M</sp-heading>
        <sp-heading size="S">Heading S</sp-heading>
        <sp-heading size="XS">Heading XS</sp-heading>
        <sp-heading size="XXS">Heading XXS</sp-heading>
      </div>
      <div class="group"><sp-label>Body</sp-label>
        <sp-detail>BODY TEXT</sp-detail>
        <sp-body>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-detail>BODY SIZES</sp-detail>
        <sp-body size="XXXL">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-body size="XXL">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-body size="XL">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-body size="L">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-body size="M">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-body size="S">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
        <sp-body size="XS">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec eleifend est mollis ligula lobortis, tempus ultricies sapien lacinia. Nulla ut turpis velit. Sed finibus dapibus diam et sollicitudin. Phasellus in ipsum nec ante elementum congue eget in leo. Morbi eleifend justo non rutrum venenatis. Fusce cursus et lectus eu facilisis. Ut laoreet felis in magna dignissim feugiat.</sp-body>
      </div>
      <div class="group"><sp-label>Label</sp-label>
        <sp-label class="safe">Label</sp-label>
        <div style="background-color: blue">
          <sp-label variant="overBackground" class="safe">Label, overBackground</sp-label>
        </div>
      </div>
      <div class="group"><sp-label>Detail</sp-label>
        <sp-detail>SOME DETAIL INFO</sp-detail>
      </div>
    </div>
    <div class="sp-tab-page" id="sp-spectrum-widgets-tab-page">
      <div class="group"><sp-label>Action Buttons</sp-label>
        <sp-detail>NO ICON</sp-detail>
        <sp-action-button> Do action </sp-action-button>
        <sp-action-button selected> Do action </sp-action-button>
        <sp-action-button disabled> Do action </sp-action-button>
        <sp-detail>WITH ICON</sp-detail>
        <sp-action-button>
          <div slot="icon" class="icon">
            <svg id="spectrum-icon-18-Edit" viewBox="0 0 36 36">
                <path
                    d="M33.567 8.2L27.8 2.432a1.215 1.215 0 0 0-.866-.353H26.9a1.371 1.371 0 0 0-.927.406L5.084 23.372a.99.99 0 0 0-.251.422L2.055 33.1c-.114.377.459.851.783.851a.251.251 0 0 0 .062-.007c.276-.063 7.866-2.344 9.311-2.778a.972.972 0 0 0 .414-.249l20.888-20.889a1.372 1.372 0 0 0 .4-.883 1.221 1.221 0 0 0-.346-.945zM11.4 29.316c-2.161.649-4.862 1.465-6.729 2.022l2.009-6.73z"
                ></path>
            </svg>
          </div>
          This is an action button
        </sp-action-button>
        <sp-detail>ICON ONLY</sp-detail>
        <sp-action-button label="Edit"><div slot="icon" class="icon"><svg id="spectrum-icon-18-Edit" viewBox="0 0 36 36"><path d="M33.567 8.2L27.8 2.432a1.215 1.215 0 0 0-.866-.353H26.9a1.371 1.371 0 0 0-.927.406L5.084 23.372a.99.99 0 0 0-.251.422L2.055 33.1c-.114.377.459.851.783.851a.251.251 0 0 0 .062-.007c.276-.063 7.866-2.344 9.311-2.778a.972.972 0 0 0 .414-.249l20.888-20.889a1.372 1.372 0 0 0 .4-.883 1.221 1.221 0 0 0-.346-.945zM11.4 29.316c-2.161.649-4.862 1.465-6.729 2.022l2.009-6.73z" ></path></svg></div></sp-action-button>
      </div>
      <div class="group"><sp-label>Buttons</sp-label>
        <sp-detail>NORMAL VARIANTS</sp-detail>
        <sp-button variant="cta">Call To Action</sp-button>
        <sp-button variant="primary">Primary</sp-button>
        <sp-button variant="secondary">Secondary</sp-button>
        <sp-button variant="warning">Warning</sp-button>
        <sp-detail>QUIET VARIANTS</sp-detail>
        <sp-button quiet variant="primary">Quiet Primary</sp-button>
        <sp-button quiet variant="secondary">Quiet Secondary</sp-button>
        <sp-button quiet variant="negative">Quiet Negative</sp-button>
        <sp-detail>WITH ICONS</sp-detail>
        <sp-icons-medium></sp-icons-medium>
        <sp-button variant="primary">Label only</sp-button>
        <sp-button variant="primary">
            <sp-icon slot="icon" size="s" name="ui:HelpMedium"></sp-icon>
            Icon + Label
        </sp-button>
        <sp-button variant="primary">
          <div slot="icon" class="icon">
            <svg
                slot="icon"
                viewBox="0 0 36 36"
                focusable="false"
                aria-hidden="true"
                role="img"
            >
                <path
                    d="M16 36a4.407 4.407 0 0 0 4-4h-8a4.407 4.407 0 0 0 4 4zm9.143-24.615c0-3.437-3.206-4.891-7.143-5.268V3a1.079 1.079 0 0 0-1.143-1h-1.714A1.079 1.079 0 0 0 14 3v3.117c-3.937.377-7.143 1.831-7.143 5.268C6.857 26.8 2 26.111 2 28.154V30h28v-1.846C30 26 25.143 26.8 25.143 11.385z"
                ></path>
            </svg>
          </div>
          SVG Icon + Label
        </sp-button>
        <sp-detail>STATES</sp-detail>
        <sp-button variant="primary">Normal</sp-button>
        <sp-button variant="primary" disabled>Disabled</sp-button>
      </div>
      <div class="group"><sp-label>Checkbox</sp-label>
        <sp-detail>REGULAR CHECKBOX</sp-detail>
        <sp-checkbox>Web component</sp-checkbox>
        <sp-detail>STATES</sp-detail>
        <sp-checkbox checked>Web component</sp-checkbox>
        <sp-checkbox indeterminate>Web component</sp-checkbox>
        <sp-checkbox disabled>Web component</sp-checkbox>
        <sp-checkbox invalid>Web component</sp-checkbox>
      </div>
      <div class="group"><sp-label>Dividers</sp-label>
        <sp-detail>DIVIDER SIZES</sp-detail>
        <sp-divider size="large"></sp-divider>
        <sp-divider size="medium"></sp-divider>
        <sp-divider size="small"></sp-divider>
      </div>
      <div class="group"><sp-label>Dropdown</sp-label>
        <sp-detail>NORMAL</sp-detail>
        <sp-dropdown placeholder="Make a selection...">
            <sp-menu slot="options">
                <sp-menu-item> Deselect </sp-menu-item>
                <sp-menu-item> Select inverse </sp-menu-item>
                <sp-menu-item> Feather... </sp-menu-item>
                <sp-menu-item> Select and mask... </sp-menu-item>
                <sp-menu-divider></sp-menu-divider>
                <sp-menu-item> Save selection </sp-menu-item>
                <sp-menu-item disabled> Make work path </sp-menu-item>
            </sp-menu>
        </sp-dropdown>
        <sp-detail>DISABLED</sp-detail>
        <sp-dropdown disabled placeholder="Make a selection...">
            <sp-menu slot="options">
                <sp-menu-item> Deselect </sp-menu-item>
                <sp-menu-item> Select inverse </sp-menu-item>
                <sp-menu-item> Feather... </sp-menu-item>
                <sp-menu-item> Select and mask... </sp-menu-item>
                <sp-menu-divider></sp-menu-divider>
                <sp-menu-item> Save selection </sp-menu-item>
                <sp-menu-item disabled> Make work path </sp-menu-item>
            </sp-menu>
        </sp-dropdown>
        <sp-detail>INVALID</sp-detail>
        <sp-dropdown invalid placeholder="Make a selection...">
            <sp-menu slot="options">
                <sp-menu-item> Deselect </sp-menu-item>
                <sp-menu-item> Select inverse </sp-menu-item>
                <sp-menu-item> Feather... </sp-menu-item>
                <sp-menu-item> Select and mask... </sp-menu-item>
                <sp-menu-divider></sp-menu-divider>
                <sp-menu-item> Save selection </sp-menu-item>
                <sp-menu-item disabled> Make work path </sp-menu-item>
            </sp-menu>
        </sp-dropdown>
      </div>
      <div class="group"><sp-label>Icon</sp-label>
        <sp-detail>UI ICON</sp-detail>
        <sp-body>
          <sp-icon name="ui:Magnifier"></sp-icon>
        </sp-body>
        <sp-detail>SIZE VARIANTS</sp-detail>
        <sp-body>
          <sp-icon size="xxs" name="ui:Magnifier"></sp-icon>
          <sp-icon size="xs" name="ui:Magnifier"></sp-icon>
          <sp-icon size="s" name="ui:Magnifier"></sp-icon>
          <sp-icon size="m" name="ui:Magnifier"></sp-icon>
          <sp-icon size="l" name="ui:Magnifier"></sp-icon>
          <sp-icon size="xl" name="ui:Magnifier"></sp-icon>
          <sp-icon size="xxl" name="ui:Magnifier"></sp-icon>
        </sp-body>
      </div>
      <div class="group"><sp-label>Link</sp-label>
        <sp-detail>STANDARD LINK</sp-detail>
        <sp-body>
          This is a <sp-link href="#">standard link</sp-link>.
        </sp-body>
        <sp-detail>QUIET LINK</sp-detail>
        <sp-body>
          This is a <sp-link quiet href="#">standard link</sp-link>.
        </sp-body>
      </div>
      <div class="group"><sp-label>Menu</sp-label>
        <sp-detail>MENU</sp-detail>
        <sp-menu>
          <sp-menu-item> Deselect </sp-menu-item>
          <sp-menu-item> Select inverse </sp-menu-item>
          <sp-menu-item> Feather... </sp-menu-item>
          <sp-menu-item> Select and mask... </sp-menu-item>
          <sp-menu-item> Save selection </sp-menu-item>
          <sp-menu-item disabled> Make work path </sp-menu-item>
        </sp-menu>
      </div>
      <div class="group"><sp-label>Number</sp-label>
        <sp-detail>NUMBER FIELD</sp-detail>
        <sp-textfield type="number" placeholder="Pick a Number"></sp-textfield>
        <sp-detail>QUIET NUMBER FIELD</sp-detail>
        <sp-textfield quiet type="number" placeholder="Pick a Number"></sp-textfield>
        <sp-detail>NUMBER FIELD VARIANTS</sp-detail>
        <sp-textfield type="number" invalid placeholder="Pick a Number"></sp-textfield>
        <sp-textfield type="number" valid placeholder="Pick a Number"></sp-textfield>
      </div>
      <div class="group"><sp-label>Password</sp-label>
        <sp-detail>PASSWORD FIELD</sp-detail>
        <sp-textfield type="password" placeholder="Password"></sp-textfield>
        <sp-detail>QUIET PASSWORD FIELD</sp-detail>
        <sp-textfield quiet type="password" placeholder="Password"></sp-textfield>
        <sp-detail>NUMBER PASSWORD VARIANTS</sp-detail>
        <sp-textfield type="password" invalid placeholder="Password"></sp-textfield>
        <sp-textfield type="password" valid placeholder="Password"></sp-textfield>
      </div>
      <div class="group"><sp-label>Radio</sp-label>
        <sp-detail>STANDARD RADIO BUTTON GROUP</sp-detail>
        <sp-radio-group selected="first" name="example">
            <sp-radio value="first">Option 1</sp-radio>
            <sp-radio value="second">Option 2</sp-radio>
            <sp-radio value="third">Option 3</sp-radio>
            <sp-radio value="fourth">Option 4</sp-radio>
        </sp-radio-group>
        <sp-detail>STATES</sp-detail>
        <sp-radio-group name="example2">
          <sp-radio checked>Checked radio button</sp-radio>
          <sp-radio invalid>Invalid radio button</sp-radio>
          <sp-radio disabled>Disabled radio button</sp-radio>
        <sp-radio-group>


      </div>
      <div class="group"><sp-label>Search</sp-label>
        <sp-detail>SEARCH FIELD</sp-detail>
        <sp-textfield type="search" placeholder="Stock Search..."></sp-textfield>
        <sp-detail>QUIET SEARCH FIELD</sp-detail>
        <sp-textfield quiet type="search" placeholder="Stock Search..."></sp-textfield>
        <sp-detail>NUMBER SEARCH VARIANTS</sp-detail>
        <sp-textfield type="search" invalid placeholder="Stock Search..."></sp-textfield>
        <sp-textfield type="search" valid placeholder="Stock Search..."></sp-textfield>
      </div>
      <div class="group"><sp-label>Slider</sp-label>
        <sp-detail>SLIDER</sp-detail>
        <sp-slider min="0" max="100" value="50"></sp-slider>
        <sp-slider min="0" max="100" value="50" disabled></sp-slider>
        <sp-detail>WITH LABEL</sp-detail>
        <sp-slider min="0" max="100" value="50"><sp-label slot="label">Slider Label</sp-label></sp-slider>
        <sp-slider min="0" max="100" value="50" disabled><sp-label slot="label">Slider Label - Disabled</sp-label></sp-slider>
        <sp-detail>FILLED</sp-detail>
        <sp-slider min="0" max="100" value="50" variant="filled"></sp-slider>
        <sp-slider min="0" max="100" value="50" variant="filled" disabled ></sp-slider>
      </div>
      <div class="group"><sp-label>Textarea</sp-label>
        <sp-detail>TEXT AREA</sp-detail>
        <sp-textarea placeholder="Enter your name" multiline></sp-textarea>
        <sp-textarea quiet placeholder="Enter your name" multiline></sp-textarea>
        <sp-textarea invalid placeholder="Enter your name" multiline></sp-textarea>
        <sp-textarea valid placeholder="Enter your name" multiline></sp-textarea>
        <sp-detail>TEXT AREA WITH LABEL</sp-detail>
        <sp-textarea placeholder="Add a comment" multiline>
          <sp-label slot="label">Feedback</sp-label>
        </sp-textarea>
      </div>
      <div class="group"><sp-label>Textfield</sp-label>
        <sp-detail>TEXT FIELD</sp-detail>
        <sp-textfield placeholder="Type Something."></sp-textfield>
        <sp-detail>QUIET TEXT FIELD</sp-detail>
        <sp-textfield quiet placeholder="Type Something."></sp-textfield>
        <sp-detail>TEXT SEARCH VARIANTS</sp-detail>
        <sp-textfield valid placeholder="Type Something."></sp-textfield>
        <sp-textfield invalid placeholder="Type Something."></sp-textfield>
        <sp-detail>TEXT FIELD WITH LABELS</sp-detail>
        <sp-textfield placeholder="Phone Number"><sp-label isrequired="true" slot="label">Phone Number</sp-label></sp-textfield>
        <br/>
        <sp-textfield placeholder="Phone Number" style="display: flex; flex-direction: row; align-items: baseline;">
          <sp-label style="padding-right: 16px" isrequired="true" slot="label">Phone Number</sp-label>
        </sp-textfield>
      </div>
      <div class="group"><sp-label>Tooltip</sp-label>
        <sp-detail>NORMAL TOOLTIP</sp-detail>
        <sp-tooltip open placement="top">Label</sp-tooltip>
        <br />
        <br />
        <sp-tooltip open placement="bottom">Label</sp-tooltip>
        <br />
        <br />
        <sp-tooltip open placement="left">Label</sp-tooltip>
        <br />
        <br />
        <sp-tooltip open placement="right">Label</sp-tooltip>
        <sp-detail>CONTROL WITH TOOLTIP</sp-detail>
        <sp-button class="tooltip">Hover over me
          <sp-tooltip open placement="top" variant="info">I'm a tooltip!</sp-tooltip>
        </sp-button>
        <sp-detail>INFORMATIVE TOOLTIP</sp-detail>
        <sp-tooltip open placement="top" variant="info">Label</sp-tooltip>
        <sp-tooltip open placement="top" variant="info">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </sp-tooltip>
        <sp-tooltip open placement="top" variant="info">
            <sp-icon size="s" name="ui:InfoSmall" slot="icon"></sp-icon>
            Label
        </sp-tooltip>
        <sp-tooltip open placement="top" variant="info">
            <sp-icon size="s" name="ui:InfoSmall" slot="icon"></sp-icon>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </sp-tooltip>
        <sp-detail>POSITIVE TOOLTIP</sp-detail>
        <sp-tooltip open placement="top" variant="positive">Label</sp-tooltip>
        <sp-tooltip open placement="top" variant="positive">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </sp-tooltip>
        <sp-tooltip open placement="top" variant="positive">
            <sp-icon size="s" name="ui:CheckmarkSmall" slot="icon"></sp-icon>
            Label
        </sp-tooltip>
        <sp-tooltip open placement="top" variant="positive">
            <sp-icon size="s" name="ui:CheckmarkSmall" slot="icon"></sp-icon>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </sp-tooltip>
        <sp-detail>NEGATIVE TOOLTIP</sp-detail>
        <sp-tooltip open placement="top" variant="negative">Label</sp-tooltip>
        <sp-tooltip open placement="top" variant="negative">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </sp-tooltip>
        <sp-tooltip open placement="top" variant="negative">
            <sp-icon size="s" name="ui:AlertSmall" slot="icon"></sp-icon>
            Label
        </sp-tooltip>
        <sp-tooltip open placement="top" variant="negative">
            <sp-icon size="s" name="ui:AlertSmall" slot="icon"></sp-icon>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </sp-tooltip>
      </div>
    </div>
    <div class="sp-tab-page" id="sp-native-tab-page">
      <div class="group"><sp-label>Buttons</sp-label>
        <button>Hi</button>
      </div>
      <div class="group"><sp-label>Checkboxes</sp-label>
        <label><input type="checkbox">Check me</label>
        <label><input type="checkbox" checked>Check me</label>
        <label><input type="checkbox" disabled>Check me</label>
      </div>
      <div class="group"><sp-label>Dialogs</sp-label>
        <sp-detail>DIALOG EXAMPLE</sp-detail>
        <button id="btnOpenDialog">Open Dialog</button>
        <dialog id="dlgExample">
          <form method="dialog">
            <sp-heading>Vectorize Images?</sp-heading>
            <sp-divider size="large"></sp-divider>
            <sp-body>Are you sure you want to vectorize the images? This might take some time.</sp-body>
            <footer>
              <sp-button variant="secondary" quiet>Don't Vectorize</sp-button>
              <sp-button variant="cta">Vectorize</sp-button>
            </footer>
          </form>
        </dialog>
        <button id="btnOpenPDialog">Open Programmatic Dialog</button>
      </div>
      <div class="group"><sp-label>Selects</sp-label>
        <label>City:
          <select>
            <option value="Amsterdam" selected>Amsterdam</option>
            <option value="New York" >New York</option>
            <option value="New Jersey">New Jersey</option>
          </select>
        </label>
      </div>
      <div class="group"><sp-label>Radio Buttons</sp-label>
        <label><input type="radio" name="radioGroup">Click me</label>
        <label><input type="radio" name="radioGroup" checked>Click me</label>
        <label><input type="radio" name="radioGroup" disabled >Click me</label>
      </div>
      <div class="group"><sp-label>Range</sp-label>
        <label>Opacity: <input type="range" min="0" max="100" value="50"></label>
      </div>
      <div class="group"><sp-label>Textarea</sp-label>
        <label>Text Area
        <textarea style="width:240px; height:60px"></textarea>
        </label>
      </div>
      <div class="group"><sp-label>Text Input</sp-label>
        <label>Text Input <input type="text" placeholder="Enter your text"/> </label>
        <label>Number Input <input type="number" placeholder="Enter your text"/> </label>
        <label>Password Input <input type="password" placeholder="Enter your text"/> </label>
      </div>
    </div>
    <div class="sp-tab-page" id="sp-html-tab-page">
      <div class="group"><sp-label>Rules</sp-label>
        <sp-detail>HR</sp-detail>
        <hr/>
      </div>
    </div>
    <div class="sp-tab-page" id="sp-events-tab-page">
      <sp-checkbox id="toggleConsole">Toggle Events Console</sp-checkbox>
      <sp-checkbox class="filter" id="chkfocus" checked>focus</sp-checkbox>
      <sp-checkbox class="filter" id="chkblur" checked>blur</sp-checkbox>
      <sp-checkbox class="filter" id="chkclick" checked>click</sp-checkbox>
      <sp-checkbox class="filter" id="chkdblclick" checked>dblclick</sp-checkbox>
      <sp-checkbox class="filter" id="chkauxclick" checked>auxclick*</sp-checkbox>
      <sp-checkbox class="filter" id="chkcontextmenu" checked>contextmenu</sp-checkbox>
      <sp-checkbox class="filter" id="chkchange" checked>change</sp-checkbox>
      <sp-checkbox class="filter" id="chkinput" checked>input</sp-checkbox>
      <sp-checkbox class="filter" id="chkkeydown" checked>keydown</sp-checkbox>
      <sp-checkbox class="filter" id="chkkeyup" checked>keyup</sp-checkbox>
      <sp-checkbox class="filter" id="chkkeypress" checked>keypress*</sp-checkbox>
      <sp-checkbox class="filter" id="chkmousedown" checked>mousedown</sp-checkbox>
      <sp-checkbox class="filter" id="chkmouseup" checked>mouseup</sp-checkbox>
      <sp-checkbox class="filter" id="chkmousemove" >mousemove</sp-checkbox>
      <sp-checkbox class="filter" id="chkmouseenter" >mouseenter</sp-checkbox>
      <sp-checkbox class="filter" id="chkmouseleave" >mouseleave</sp-checkbox>
      <sp-checkbox class="filter" id="chkmouseover" >mouseover</sp-checkbox>
      <sp-checkbox class="filter" id="chkmouseout" >mouseout</sp-checkbox>
      <sp-checkbox class="filter" id="chkmousewheel" >mousewheel*</sp-checkbox>
      <sp-checkbox class="filter" id="chkwheel" >wheel*</sp-checkbox>
      <sp-body>* indicates non-functioning</sp-body>
    </div>
    <div id="console" class="console">
      <sp-body id="logs"></sp-body>
    </div>
  </div>