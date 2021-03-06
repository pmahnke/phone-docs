---
Title: ubuntuuitoolkit
---

# ubuntuuitoolkit

<!-- Start Namespace Content -->
<p>Ubuntu UI Toolkit Autopilot tests and helpers.</p>
<dl class="class">
<dt id="ubuntuuitoolkit.AppHeader">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">AppHeader</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>AppHeader Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.click_action_button">
<tt class="descname">click_action_button</tt><big>(</big><em>action_object_name</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.click_action_button" title="Permalink to this definition">&para;</a></dt>
<dd><p>Click an action button of the header.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>object_name</strong> &#8211; The QML objectName property of the action</td>
</tr>
<tr class="field-even field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-even field"><td>&nbsp;</td><td class="field-body">If there is no action button with that object
name.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.click_back_button">
<tt class="descname">click_back_button</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.click_back_button" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.click_custom_back_button">
<tt class="descname">click_custom_back_button</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.click_custom_back_button" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.ensure_visible">
<tt class="descname">ensure_visible</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.ensure_visible" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.get_selected_section_index">
<tt class="descname">get_selected_section_index</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.get_selected_section_index" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.switch_to_next_tab">
<tt class="descname">switch_to_next_tab</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.switch_to_next_tab" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open the next tab.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the main view has no tabs.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.switch_to_section_by_index">
<tt class="descname">switch_to_section_by_index</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.switch_to_section_by_index" title="Permalink to this definition">&para;</a></dt>
<dd><p>Select a section in the header divider</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>index</strong> &#8211; The index of the section to select</td>
</tr>
<tr class="field-even field"><th class="field-name" colspan="2">Raises ToolkitEmulatorException:</th></tr>
<tr class="field-even field"><td>&nbsp;</td><td class="field-body">If the selection index is out of
range or useDeprecatedToolbar is set.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.switch_to_tab_by_index">
<tt class="descname">switch_to_tab_by_index</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.switch_to_tab_by_index" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open a tab. This only supports the new tabs in the header</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>index</strong> &#8211; The index of the tab to open.</td>
</tr>
<tr class="field-even field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-even field"><td>&nbsp;</td><td class="field-body">If the tab index is out
of range or useDeprecatedToolbar is set.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.AppHeader.wait_for_animation">
<tt class="descname">wait_for_animation</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.AppHeader.wait_for_animation" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
</dd></dl>
<dl class="function">
<dt id="ubuntuuitoolkit.check_autopilot_version">
<tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">check_autopilot_version</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.check_autopilot_version" title="Permalink to this definition">&para;</a></dt>
<dd><p>Check that the Autopilot installed version matches the one required.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the installed Autopilot version does&#8217;t
match the required by the custom proxy objects.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.CheckBox">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">CheckBox</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.CheckBox" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>CheckBox Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.CheckBox.change_state">
<tt class="descname">change_state</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.CheckBox.change_state" title="Permalink to this definition">&para;</a></dt>
<dd><p>Change the state of a CheckBox.</p>
<p>If it is checked, it will be unchecked. If it is unchecked, it will be
checked.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>time_out</strong> &#8211; number of seconds to wait for the CheckBox state
to change. Default is 10.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.CheckBox.check">
<tt class="descname">check</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.CheckBox.check" title="Permalink to this definition">&para;</a></dt>
<dd><p>Check a CheckBox, if its not already checked.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>timeout</strong> &#8211; number of seconds to wait for the CheckBox to be
checked. Default is 10.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.CheckBox.uncheck">
<tt class="descname">uncheck</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.CheckBox.uncheck" title="Permalink to this definition">&para;</a></dt>
<dd><p>Uncheck a CheckBox, if its not already unchecked.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>timeout</strong> &#8211; number of seconds to wait for the CheckBox to be
unchecked. Default is 10.</td>
</tr>
</tbody>
</table>
</dd></dl>
</dd></dl>
<dl class="function">
<dt id="ubuntuuitoolkit.get_keyboard">
<tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">get_keyboard</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.get_keyboard" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the keyboard device.</p>
</dd></dl>
<dl class="function">
<dt id="ubuntuuitoolkit.get_pointing_device">
<tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">get_pointing_device</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.get_pointing_device" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the pointing device depending on the platform.</p>
<p>If the platform is <cite>Desktop</cite>, the pointing device will be a <cite>Mouse</cite>.
If not, the pointing device will be <cite>Touch</cite>.</p>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.Header">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">Header</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Header" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._header.AppHeader</span></tt></p>
<p>Autopilot helper for the deprecated Header.</p>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.Dialog">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">Dialog</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Dialog" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>Autopilot helper for the Dialog component.</p>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.UCListItem">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">UCListItem</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UCListItem" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>Base class to emulate swipe for leading and trailing actions.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.UCListItem.toggle_selected">
<tt class="descname">toggle_selected</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UCListItem.toggle_selected" title="Permalink to this definition">&para;</a></dt>
<dd><p>Toggles selected state of the ListItem.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.UCListItem.trigger_leading_action">
<tt class="descname">trigger_leading_action</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UCListItem.trigger_leading_action" title="Permalink to this definition">&para;</a></dt>
<dd><p>Swipe the item in from left to right to open leading actions
and click on the button representing the requested action.</p>
<dl class="docutils">
<dt>parameters: action_objectName - object name of the action to be</dt>
<dd>triggered.
wait_function - a custom wait function to wait till the
action is triggered</dd>
</dl>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.UCListItem.trigger_trailing_action">
<tt class="descname">trigger_trailing_action</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UCListItem.trigger_trailing_action" title="Permalink to this definition">&para;</a></dt>
<dd><p>Swipe the item in from right to left to open trailing actions
and click on the button representing the requested action.</p>
<dl class="docutils">
<dt>parameters: action_objectName - object name of the action to be</dt>
<dd>triggered.
wait_function - a custom wait function to wait till the
action is triggered</dd>
</dl>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.MainView">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">MainView</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>MainView Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.click_action_button">
<tt class="descname">click_action_button</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.click_action_button" title="Permalink to this definition">&para;</a></dt>
<dd><p>Click the specified button.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>action_object_name</strong> &#8211; the objectName of the action to trigger.</td>
</tr>
<tr class="field-even field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-even field"><td>&nbsp;</td><td class="field-body">The requested button is not available.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.close_toolbar">
<tt class="descname">close_toolbar</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.close_toolbar" title="Permalink to this definition">&para;</a></dt>
<dd><p>Close the toolbar if it is opened.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the main view has no toolbar.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.get_action_selection_popover">
<tt class="descname">get_action_selection_popover</tt><big>(</big><em>object_name</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.get_action_selection_popover" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return an ActionSelectionPopover custom proxy object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>object_name</strong> &#8211; The QML objectName property of the popover.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.get_header">
<tt class="descname">get_header</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.get_header" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the AppHeader custom proxy object of the MainView.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.get_tabs">
<tt class="descname">get_tabs</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.get_tabs" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the Tabs custom proxy object of the MainView.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the main view has no tabs.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.get_text_input_context_menu">
<tt class="descname">get_text_input_context_menu</tt><big>(</big><em>object_name</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.get_text_input_context_menu" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return a TextInputContextMenu emulator.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>object_name</strong> &#8211; The QML objectName property of the popover.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.get_toolbar">
<tt class="descname">get_toolbar</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.get_toolbar" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the Toolbar custom proxy object of the MainView.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the main view has no toolbar.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.go_back">
<tt class="descname">go_back</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.go_back" title="Permalink to this definition">&para;</a></dt>
<dd><p>Go to the previous page.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.open_toolbar">
<tt class="descname">open_toolbar</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.open_toolbar" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open the toolbar if it is not already opened.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Returns:</th><td class="field-body">The toolbar.</td>
</tr>
<tr class="field-even field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-even field"><td>&nbsp;</td><td class="field-body">If the main view has no toolbar.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.switch_to_next_tab">
<tt class="descname">switch_to_next_tab</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.switch_to_next_tab" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open the next tab.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Returns:</th><td class="field-body">The newly opened tab.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.switch_to_previous_tab">
<tt class="descname">switch_to_previous_tab</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.switch_to_previous_tab" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open the previous tab.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Returns:</th><td class="field-body">The newly opened tab.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.switch_to_tab">
<tt class="descname">switch_to_tab</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.switch_to_tab" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open a tab.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>object_name</strong> &#8211; The QML objectName property of the tab.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">The newly opened tab.</td>
</tr>
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If there is no tab with that object
name.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.MainView.switch_to_tab_by_index">
<tt class="descname">switch_to_tab_by_index</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.switch_to_tab_by_index" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open a tab.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>index</strong> &#8211; The index of the tab to open.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">The newly opened tab.</td>
</tr>
<tr class="field-odd field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the tab index
is out of range.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="classmethod">
<dt id="ubuntuuitoolkit.MainView.validate_dbus_object">
<em class="property">classmethod </em><tt class="descname">validate_dbus_object</tt><big>(</big><em>path</em>, <em>state</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.MainView.validate_dbus_object" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.OptionSelector">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">OptionSelector</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.OptionSelector" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>OptionSelector Autopilot custom proxy object</p>
<dl class="method">
<dt id="ubuntuuitoolkit.OptionSelector.get_current_label">
<tt class="descname">get_current_label</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.OptionSelector.get_current_label" title="Permalink to this definition">&para;</a></dt>
<dd><p>gets the text of the currently selected item</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.OptionSelector.get_option_count">
<tt class="descname">get_option_count</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.OptionSelector.get_option_count" title="Permalink to this definition">&para;</a></dt>
<dd><p>Gets the number of items in the option selector</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.OptionSelector.get_selected_index">
<tt class="descname">get_selected_index</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.OptionSelector.get_selected_index" title="Permalink to this definition">&para;</a></dt>
<dd><p>Gets the current selected index of the QQuickListView</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.OptionSelector.get_selected_text">
<tt class="descname">get_selected_text</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.OptionSelector.get_selected_text" title="Permalink to this definition">&para;</a></dt>
<dd><p>gets the text of the currently selected item</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.OptionSelector.select_option">
<tt class="descname">select_option</tt><big>(</big><em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.OptionSelector.select_option" title="Permalink to this definition">&para;</a></dt>
<dd><p>Select delegate in option selector</p>
<dl class="docutils">
<dt>Example usage::</dt>
<dd>select_option(objectName=&#8221;myOptionSelectorDelegate&#8221;)
select_option(&#8216;Label&#8217;, text=&#8221;some_text_here&#8221;)</dd>
</dl>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>kwargs</strong> &#8211; keywords used to find property(s) of delegate in
option selector</td>
</tr>
</tbody>
</table>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.QQuickFlickable">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">QQuickFlickable</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._flickable.Scrollable</span></tt></p>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickFlickable.pull_to_refresh">
<tt class="descname">pull_to_refresh</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable.pull_to_refresh" title="Permalink to this definition">&para;</a></dt>
<dd><p>Pulls the flickable down and triggers a refresh on it.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name" colspan="2">Raises <a class="reference internal" href="#ubuntuuitoolkit.ToolkitException" title="ubuntuuitoolkit.ToolkitException">ubuntuuitoolkit.ToolkitException</a>:</th></tr>
<tr class="field-odd field"><td>&nbsp;</td><td class="field-body">If the flickable has no pull
to release functionality.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickFlickable.swipe_child_into_view">
<tt class="descname">swipe_child_into_view</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable.swipe_child_into_view" title="Permalink to this definition">&para;</a></dt>
<dd><p>Make the child visible.</p>
<p>Currently it works only when the object needs to be swiped vertically.
TODO implement horizontal swiping. &#8211;elopio - 2014-03-21</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickFlickable.swipe_to_bottom">
<tt class="descname">swipe_to_bottom</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable.swipe_to_bottom" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickFlickable.swipe_to_show_more_above">
<tt class="descname">swipe_to_show_more_above</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable.swipe_to_show_more_above" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickFlickable.swipe_to_show_more_below">
<tt class="descname">swipe_to_show_more_below</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable.swipe_to_show_more_below" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickFlickable.swipe_to_top">
<tt class="descname">swipe_to_top</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickFlickable.swipe_to_top" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.QQuickGridView">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">QQuickGridView</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickGridView" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._flickable.QQuickFlickable</span></tt></p>
<p>Autopilot helper for the QQuickGridView component.</p>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.QQuickListView">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">QQuickListView</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickListView" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._flickable.QQuickFlickable</span></tt></p>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickListView.click_element">
<tt class="descname">click_element</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickListView.click_element" title="Permalink to this definition">&para;</a></dt>
<dd><p>Click an element from the list.</p>
<p>It swipes the element into view if it&#8217;s center is not visible.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>objectName</strong> &#8211; The objectName property of the element to click.</li>
<li><strong>direction</strong> &#8211; The direction where the element is, it can be
either &#8216;above&#8217; or &#8216;below&#8217;. Default value is None, which means we
don&#8217;t know where the object is and we will need to search the full
list.</li>
</ul>
</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickListView.drag_item">
<tt class="descname">drag_item</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickListView.drag_item" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.QQuickListView.enable_select_mode">
<tt class="descname">enable_select_mode</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.QQuickListView.enable_select_mode" title="Permalink to this definition">&para;</a></dt>
<dd><p>Default implementation to enable select mode. Performs a long tap
over the first list item in the ListView. The delegates must be
the new ListItem components.</p>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.TabBar">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">TabBar</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TabBar" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>TabBar Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.TabBar.switch_to_next_tab">
<tt class="descname">switch_to_next_tab</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TabBar.switch_to_next_tab" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open the next tab.</p>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.Tabs">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">Tabs</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Tabs" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>Tabs Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.Tabs.get_current_tab">
<tt class="descname">get_current_tab</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Tabs.get_current_tab" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the currently selected tab.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.Tabs.get_number_of_tabs">
<tt class="descname">get_number_of_tabs</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Tabs.get_number_of_tabs" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return the number of tabs.</p>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.TextArea">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">TextArea</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TextArea" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._textfield.TextField</span></tt></p>
<p>TextArea autopilot emulator.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.TextArea.clear">
<tt class="descname">clear</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TextArea.clear" title="Permalink to this definition">&para;</a></dt>
<dd><p>Clear the text area.</p>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.TextField">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">TextField</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TextField" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>TextField Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.TextField.clear">
<tt class="descname">clear</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TextField.clear" title="Permalink to this definition">&para;</a></dt>
<dd><p>Clear the text field.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.TextField.is_empty">
<tt class="descname">is_empty</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TextField.is_empty" title="Permalink to this definition">&para;</a></dt>
<dd><p>Return True if the text field is empty. False otherwise.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.TextField.write">
<tt class="descname">write</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.TextField.write" title="Permalink to this definition">&para;</a></dt>
<dd><p>Write into the text field.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>text</strong> &#8211; The text to write.</li>
<li><strong>clear</strong> &#8211; If True, the text field will be cleared before
writing the text. If False, the text will be appended at the end
of the text field. Default is True.</li>
</ul>
</td>
</tr>
</tbody>
</table>
</dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.Toolbar">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">Toolbar</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Toolbar" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._common.UbuntuUIToolkitCustomProxyObjectBase</span></tt></p>
<p>Toolbar Autopilot custom proxy object.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.Toolbar.click_back_button">
<tt class="descname">click_back_button</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Toolbar.click_back_button" title="Permalink to this definition">&para;</a></dt>
<dd><p>Click the back button of the toolbar.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.Toolbar.click_button">
<tt class="descname">click_button</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Toolbar.click_button" title="Permalink to this definition">&para;</a></dt>
<dd><p>Click a button of the toolbar.</p>
<p>The toolbar should be opened before clicking the button, or an
exception will be raised. If the toolbar is closed for some reason
(e.g., timer finishes) after moving the mouse cursor and before
clicking the button, it is re-opened automatically by this function.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>object_name</strong> &#8211; The QML objectName property of the button.</td>
</tr>
<tr class="field-even field"><th class="field-name" colspan="2">Raises ToolkitException:</th></tr>
<tr class="field-even field"><td>&nbsp;</td><td class="field-body">If there is no button with that object
name.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.Toolbar.close">
<tt class="descname">close</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Toolbar.close" title="Permalink to this definition">&para;</a></dt>
<dd><p>Close the toolbar if it&#8217;s opened.</p>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.Toolbar.open">
<tt class="descname">open</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.Toolbar.open" title="Permalink to this definition">&para;</a></dt>
<dd><p>Open the toolbar if it&#8217;s not already opened.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Returns:</th><td class="field-body">The toolbar.</td>
</tr>
</tbody>
</table>
</dd></dl>
</dd></dl>
<dl class="exception">
<dt id="ubuntuuitoolkit.ToolkitException">
<em class="property">exception </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">ToolkitException</tt><a class="headerlink" href="#ubuntuuitoolkit.ToolkitException" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">exceptions.Exception</span></tt></p>
<p>Exception raised when there is an error with the custom proxy object.</p>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.UbuntuListView11">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">UbuntuListView11</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuListView11" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">ubuntuuitoolkit._custom_proxy_objects._qquicklistview.QQuickListView</span></tt></p>
<p>Autopilot helper for the UbuntuListView 1.1.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.UbuntuListView11.manual_refresh_nowait">
<tt class="descname">manual_refresh_nowait</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuListView11.manual_refresh_nowait" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.UbuntuListView11.manual_refresh_wait">
<tt class="descname">manual_refresh_wait</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuListView11.manual_refresh_wait" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.UbuntuListView11.pull_to_refresh_enabled">
<tt class="descname">pull_to_refresh_enabled</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuListView11.pull_to_refresh_enabled" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.UbuntuListView11.wait_refresh_completed">
<tt class="descname">wait_refresh_completed</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuListView11.wait_refresh_completed" title="Permalink to this definition">&para;</a></dt>
<dd></dd></dl>
</dd></dl>
<dl class="class">
<dt id="ubuntuuitoolkit.UbuntuUIToolkitCustomProxyObjectBase">
<em class="property">class </em><tt class="descclassname">ubuntuuitoolkit.</tt><tt class="descname">UbuntuUIToolkitCustomProxyObjectBase</tt><big>(</big><em>*args</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuUIToolkitCustomProxyObjectBase" title="Permalink to this definition">&para;</a></dt>
<dd><p>Bases: <tt class="xref py py-class docutils literal"><span class="pre">autopilot.introspection.dbus.CustomEmulatorBase</span></tt></p>
<p>A base class for all the Ubuntu UI Toolkit custom proxy objects.</p>
<dl class="method">
<dt id="ubuntuuitoolkit.UbuntuUIToolkitCustomProxyObjectBase.is_flickable">
<tt class="descname">is_flickable</tt><big>(</big><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuUIToolkitCustomProxyObjectBase.is_flickable" title="Permalink to this definition">&para;</a></dt>
<dd><p>Check if the object is flickable.</p>
<p>If the object has a flicking attribute, we consider it as a flickable.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Returns:</th><td class="field-body">True if the object is flickable. False otherwise.</td>
</tr>
</tbody>
</table>
</dd></dl>
<dl class="method">
<dt id="ubuntuuitoolkit.UbuntuUIToolkitCustomProxyObjectBase.swipe_into_view">
<tt class="descname">swipe_into_view</tt><big>(</big><em>instance</em>, <em>*args</em>, <em>**kwargs</em><big>)</big><a class="headerlink" href="#ubuntuuitoolkit.UbuntuUIToolkitCustomProxyObjectBase.swipe_into_view" title="Permalink to this definition">&para;</a></dt>
<dd><p>Make the object visible.</p>
<p>Currently it works only when the object needs to be swiped vertically.
TODO implement horizontal swiping. &#8211;elopio - 2014-03-21</p>
</dd></dl>
</dd></dl>
<!-- End Namespace Content -->
