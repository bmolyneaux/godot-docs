.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the EditorInterface.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_EditorInterface:

EditorInterface
===============

**Inherits:** :ref:`Node<class_node>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------

Editor interface and main components.

Member Functions
----------------

+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`edit_resource<class_EditorInterface_edit_resource>` **(** :ref:`Resource<class_resource>` resource **)**                                          |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Control<class_control>`                              | :ref:`get_base_control<class_EditorInterface_get_base_control>` **(** **)**                                                                             |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Node<class_node>`                                    | :ref:`get_edited_scene_root<class_EditorInterface_get_edited_scene_root>` **(** **)**                                                                   |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`EditorSettings<class_editorsettings>`                | :ref:`get_editor_settings<class_EditorInterface_get_editor_settings>` **(** **)**                                                                       |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Control<class_control>`                              | :ref:`get_editor_viewport<class_EditorInterface_get_editor_viewport>` **(** **)**                                                                       |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_array>`                                  | :ref:`get_open_scenes<class_EditorInterface_get_open_scenes>` **(** **)** const                                                                         |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`EditorFileSystem<class_editorfilesystem>`            | :ref:`get_resource_filesystem<class_EditorInterface_get_resource_filesystem>` **(** **)**                                                               |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`EditorResourcePreview<class_editorresourcepreview>`  | :ref:`get_resource_previewer<class_EditorInterface_get_resource_previewer>` **(** **)**                                                                 |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`ScriptEditor<class_scripteditor>`                    | :ref:`get_script_editor<class_EditorInterface_get_script_editor>` **(** **)**                                                                           |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`                                | :ref:`get_selected_path<class_EditorInterface_get_selected_path>` **(** **)** const                                                                     |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`EditorSelection<class_editorselection>`              | :ref:`get_selection<class_EditorInterface_get_selection>` **(** **)**                                                                                   |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`inspect_object<class_EditorInterface_inspect_object>` **(** :ref:`Object<class_object>` object, :ref:`String<class_string>` for_property="" **)** |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`bool<class_bool>`                                    | :ref:`is_plugin_enabled<class_EditorInterface_is_plugin_enabled>` **(** :ref:`String<class_string>` plugin **)** const                                  |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Array<class_array>`                                  | :ref:`make_mesh_previews<class_EditorInterface_make_mesh_previews>` **(** :ref:`Array<class_array>` meshes, :ref:`int<class_int>` preview_size **)**    |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`open_scene_from_path<class_EditorInterface_open_scene_from_path>` **(** :ref:`String<class_string>` scene_filepath **)**                          |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`reload_scene_from_path<class_EditorInterface_reload_scene_from_path>` **(** :ref:`String<class_string>` scene_filepath **)**                      |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`int<class_int>`                                      | :ref:`save_scene<class_EditorInterface_save_scene>` **(** **)**                                                                                         |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`save_scene_as<class_EditorInterface_save_scene_as>` **(** :ref:`String<class_string>` path, :ref:`bool<class_bool>` with_preview=true **)**       |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`select_file<class_EditorInterface_select_file>` **(** :ref:`String<class_string>` p_file **)**                                                    |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+
| void                                                       | :ref:`set_plugin_enabled<class_EditorInterface_set_plugin_enabled>` **(** :ref:`String<class_string>` plugin, :ref:`bool<class_bool>` enabled **)**     |
+------------------------------------------------------------+---------------------------------------------------------------------------------------------------------------------------------------------------------+

Description
-----------

Editor interface. Allows saving and (re-)loading scenes, rendering mesh previews, inspecting and editing resources and objects and provides access to :ref:`EditorSettings<class_editorsettings>`, :ref:`EditorFileSystem<class_editorfilesystem>`, :ref:`EditorResourcePreview<class_editorresourcepreview>`\ er, :ref:`ScriptEditor<class_scripteditor>`, the editor viewport, as well as information about scenes. Also see :ref:`EditorPlugin<class_editorplugin>` and :ref:`EditorScript<class_editorscript>`.

Member Function Description
---------------------------

.. _class_EditorInterface_edit_resource:

- void **edit_resource** **(** :ref:`Resource<class_resource>` resource **)**

Edits the given :ref:`Resource<class_resource>`.

.. _class_EditorInterface_get_base_control:

- :ref:`Control<class_control>` **get_base_control** **(** **)**

Returns the base :ref:`Control<class_control>`.

.. _class_EditorInterface_get_edited_scene_root:

- :ref:`Node<class_node>` **get_edited_scene_root** **(** **)**

Returns the edited scene's root :ref:`Node<class_node>`.

.. _class_EditorInterface_get_editor_settings:

- :ref:`EditorSettings<class_editorsettings>` **get_editor_settings** **(** **)**

Returns the :ref:`EditorSettings<class_editorsettings>`.

.. _class_EditorInterface_get_editor_viewport:

- :ref:`Control<class_control>` **get_editor_viewport** **(** **)**

Returns the editor :ref:`Viewport<class_viewport>`.

.. _class_EditorInterface_get_open_scenes:

- :ref:`Array<class_array>` **get_open_scenes** **(** **)** const

Returns an :ref:`Array<class_array>` of the currently opened scenes.

.. _class_EditorInterface_get_resource_filesystem:

- :ref:`EditorFileSystem<class_editorfilesystem>` **get_resource_filesystem** **(** **)**

Returns the :ref:`EditorFileSystem<class_editorfilesystem>`.

.. _class_EditorInterface_get_resource_previewer:

- :ref:`EditorResourcePreview<class_editorresourcepreview>` **get_resource_previewer** **(** **)**

Returns the :ref:`EditorResourcePreview<class_editorresourcepreview>`\ er.

.. _class_EditorInterface_get_script_editor:

- :ref:`ScriptEditor<class_scripteditor>` **get_script_editor** **(** **)**

Returns the :ref:`ScriptEditor<class_scripteditor>`.

.. _class_EditorInterface_get_selected_path:

- :ref:`String<class_string>` **get_selected_path** **(** **)** const

.. _class_EditorInterface_get_selection:

- :ref:`EditorSelection<class_editorselection>` **get_selection** **(** **)**

Returns the :ref:`EditorSelection<class_editorselection>`.

.. _class_EditorInterface_inspect_object:

- void **inspect_object** **(** :ref:`Object<class_object>` object, :ref:`String<class_string>` for_property="" **)**

Shows the given property on the given ``object`` in the Editor's Inspector dock.

.. _class_EditorInterface_is_plugin_enabled:

- :ref:`bool<class_bool>` **is_plugin_enabled** **(** :ref:`String<class_string>` plugin **)** const

Returns the enabled status of a plugin. The plugin name is the same as its directory name.

.. _class_EditorInterface_make_mesh_previews:

- :ref:`Array<class_array>` **make_mesh_previews** **(** :ref:`Array<class_array>` meshes, :ref:`int<class_int>` preview_size **)**

Returns mesh previews rendered at the given size as an :ref:`Array<class_array>` of :ref:`Texture<class_texture>`\ s.

.. _class_EditorInterface_open_scene_from_path:

- void **open_scene_from_path** **(** :ref:`String<class_string>` scene_filepath **)**

Opens the scene at the given path.

.. _class_EditorInterface_reload_scene_from_path:

- void **reload_scene_from_path** **(** :ref:`String<class_string>` scene_filepath **)**

Reloads the scene at the given path.

.. _class_EditorInterface_save_scene:

- :ref:`int<class_int>` **save_scene** **(** **)**

Saves the scene. Returns either OK or ERR_CANT_CREATE. See :ref:`@GlobalScope<class_@globalscope>` constants.

.. _class_EditorInterface_save_scene_as:

- void **save_scene_as** **(** :ref:`String<class_string>` path, :ref:`bool<class_bool>` with_preview=true **)**

Saves the scene as a file at ``path``.

.. _class_EditorInterface_select_file:

- void **select_file** **(** :ref:`String<class_string>` p_file **)**

.. _class_EditorInterface_set_plugin_enabled:

- void **set_plugin_enabled** **(** :ref:`String<class_string>` plugin, :ref:`bool<class_bool>` enabled **)**

Sets the enabled status of a plugin. The plugin name is the same as its directory name.


