# Summary

* [Introduction](README.md)
   * [What's New With 4.0.0](introduction/whats_new_with_400.md)
       * [WireBox 2.0.0](introduction/whats_new/wirebox_200.md)
       * [CacheBox 2.0.0](introduction/whats_new/cachebox_200.md)
       * [LogBox 2.0.0](introduction/whats_new/logbox_200.md)
   * [Upgrading to ColdBox 4.0.0](introduction/upgrading_to_coldbox_400.md)
   * [About This Book](introduction/about_this_book.md)
   * [Author](introduction/author.md)
* [Overview](overview/index.md)
   * [What is MVC](overview/what_is_mvc.md)
   * [What is ColdBox](overview/what_is_coldbox.md)
   * [How ColdBox Works](overview/how_coldbox_works.md)
       * [ColdBox Life Cycles](overview/coldbox_life_cycles/index.md)
           * [MVC Lifecycle](overview/coldbox_life_cycles/mvc_lifecycle.md)
           * [Proxy Lifecycle](overview/coldbox_life_cycles/proxy_lifecycle.md)
   * [Installation](overview/installation.md)
   * [Creating An Application](overview/creating_an_application.md)
   * Conventions Over Configuration
   * Hello Example
   * Running An Application
   * Reiniting An Application
   * Testing An Application
* [Configuration](configuration/index.md)
   * [Conventions](configuration/conventions.md)
   * [Directory Structure](configuration/directory_structure.md)
   * [ColdBox.cfc](configuration/coldboxcfc/index.md)
       * [Configuration Directives](configuration/coldboxcfc/index.md)
           * [CacheBox](configuration/coldboxcfc/configuration_directives/cachebox.md)
           * [ColdBox](configuration/coldboxcfc/configuration_directives/coldbox.md)
           * [Conventions](configuration/coldboxcfc/configuration_directives/conventions.md)
           * [Datasources](configuration/coldboxcfc/configuration_directives/datasources.md)
           * [Environments](configuration/coldboxcfc/configuration_directives/environments.md)
           * [Flash](configuration/coldboxcfc/configuration_directives/flash.md)
           * [InterceptorSettings](configuration/coldboxcfc/configuration_directives/interceptorsettings.md)
           * [Interceptors](configuration/coldboxcfc/configuration_directives/interceptors.md)
           * [Layouts](configuration/coldboxcfc/configuration_directives/layouts.md)
           * [LayoutSettings](configuration/coldboxcfc/configuration_directives/layoutsettings.md)
           * [LogBox](configuration/coldboxcfc/configuration_directives/logbox.md)
           * [Modules](configuration/coldboxcfc/configuration_directives/modules.md)
           * [Settings](configuration/coldboxcfc/configuration_directives/settings.md)
           * [WireBox](configuration/coldboxcfc/configuration_directives/wirebox.md)
       * [Configuration Interceptor](configuration/coldboxcfc/configuration_interceptor.md)
   * [Using Settings](configuration/using_settings.md)
   * [Bootstrapper](configuration/bootstrapper.md)
* [Event Handlers](event_handlers/index.md)
   * [Locations](event_handlers/locations.md)
   * [Composed Properties](event_handlers/composed_properties.md)
   * [How are events called?](event_handlers/how_are_events_called.md)
   * [Get/Set Request Values](event_handlers/getset_request_values.md)
   * [Setting Views](event_handlers/setting_views.md)
   * [Relocating](event_handlers/relocating.md)
   * [Rendering Data](event_handlers/rendering_data.md)
   * [Model Integration](event_handlers/model_integration/index.md)
       * [Model Data Binding](event_handlers/model_integration/model_data_binding.md)
       * [Advanced Data Binding](event_handlers/model_integration/advanced_data_binding.md)
   * [Interception Methods](event_handlers/handler_interception_methods.md)
       * [Pre Advices](event_handlers/advices/pre_advices.md)
       * [Post Advices](event_handlers/advices/post_advices.md)
       * [Around Advices](event_handlers/advices/around_advices.md)
   * [HTTP Method Security](event_handlers/http_method_security.md)
   * [Convention Methods](event_handlers/convention_methods.md)
   * [Executing Events](event_handlers/executing_events.md)
   * [Event Caching](event_handlers/event_caching.md)
   * [Validation](event_handlers/validation.md)
   * [Best Practices](event_handlers/best_practices.md)
   * [Testing Handlers](event_handlers/testing_handlers.md)
* [Request Context](request_context/index.md)
   * [How Does It Work](request_context/how_does_it_work.md)
   * [Event Handlers](request_context/event_handlers.md)
   * [Views](request_context/views.md)
   * [Interceptors](request_context/interceptors.md)
   * [Plugins](request_context/plugins.md)
   * [What Can I Do With It?](request_context/what_can_i_do_with_it.md)
   * [Extending The Request Context](request_context/extending_the_request_context.md)
   * [Summary](request_context/summary.md)
   * [Request Context Decorator](request_context/request_context_decorator/index.md)
       * [For What Can I Use This?](request_context/request_context_decorator/for_what_can_i_use_this.md)
       * [Configuration](request_context/request_context_decorator/configuration.md)
       * [Conclusion](request_context/request_context_decorator/conclusion.md)
* [Models](models/index.md)
   * [Domain Modeling](models/domain_modeling/index.md)
       * [Service Layer](models/models/domain_modeling/service_layer.md)
       * [Data Layers](models/models/domain_modeling/data_layers.md)
       * [Book](models/models/domain_modeling/book.md)
   * [Conventions Location](models/conventions_location.md)
   * [WireBox Binder](models/wirebox_binder.md)
   * [Super Tupe Usage Methods](models/super_tupe_usage_methods.md)
   * [Injection DSL](models/injection_dsl/index.md)
       * [Model Object Namespace](models/injection_dsl/model_object_namespace.md)
       * [EntityService Namespace](models/injection_dsl/entityservice_namespace.md)
       * [ColdBox Namespace](models/injection_dsl/coldbox_namespace.md)
   * [Object Scopes](models/object_scopes.md)
   * [Mappings Objects](models/mappings_objects.md)
   * [Coding: Solo Style](models/coding_solo_style/index.md)
       * [Datasource](models/coding_solo_style/datasource.md)
       * [Contact.cfc](models/coding_solo_style/contactcfc.md)
       * [ContactDAO.cfc](models/coding_solo_style/contactdaocfc.md)
       * [ContactService.cfc](models/coding_solo_style/contactservicecfc.md)
       * [Contacts Handler](models/coding_solo_style/contacts_handler.md)
       * [Summary](models/coding_solo_style/summary.md)
   * [Coding: ActiveEntity Style](coding_activeentity_style/index.md)
       * [ORM](coding_activeentity_style/orm.md)
       * [Contact.cfc](coding_activeentity_style/contactcfc.md)
       * [Contacts Handler](coding_activeentity_style/contacts_handler.md)
       * [Views](coding_activeentity_style/views.md)
       * [Summary](coding_activeentity_style/summary.md)
   * [Coding: Virtual Service Layer](coding_virtual_service_layer/index.md)
       * [ORM](coding_virtual_service_layer/orm.md)
       * [Contacts.cfc](coding_virtual_service_layer/contacts.md)
       * [Contacts Handler](coding_virtual_service_layer/contacts_handler.md)
       * [Views](coding_virtual_service_layer/views.md)
       * [Summary](coding_virtual_service_layer/summary.md)
* [Routing](routing/index.md)
   * [Requirements](routing/requirements.md)
       * [Rewrite Rules](Routing/rewrite_rules.md)
   * [Routes Configuration](Routing/routes_configuration.md)
   * [URL Mappings](Routing/url_mappings.md)
       * [Adding Routes](Routing/adding_routes.md)
           * [Routing by Convention](Routing/routing_by_convention.md)
           * [Handler Routing](Routing/handler_routing.md)
           * [RESTful Action Routing](Routing/restful_action_routing.md)
           * [View Routing](Routing/view_routing.md)
           * [Pattern Placeholders](Routing/pattern_placeholders.md)
           * [Numeric Placeholder](Routing/numeric_placeholder.md)
           * [Alpha Placeholder](Routing/alpha_placeholder.md)
           * [Dynamic handler/action Placeholders](Routing/dynamic_handleraction_placeholders.md)
           * [Regular Expression Placeholder](Routing/regular_expression_placeholder.md)
           * [Optional Placeholders](Routing/optional_placeholders.md)
           * [Adding variables per route](Routing/adding_variables_per_route.md)
       * [Route Responses](Routing/route_responses.md)
       * [Route Conditions](Routing/route_conditions.md)
       * [URL Mapping Namespaces](Routing/url_mapping_namespaces.md)
       * [Module Routes](Routing/module_routes.md)
       * [With Clousures](Routing/with_clousures.md)
   * [Pathinfo Providers](Routing/pathinfo_providers.md)
   * [event.buildLink()](Routing/eventbuildlink.md)
   * [HTML base tag](Routing/html_base_tag.md)
* [Interceptors](interceptors/interceptors.md)
* [Modules](modules/index.md)
* [ColdBox Proxy](proxy/index.md)
   * [Getting Started](proxy/getting_started.md)
       * [AppMapping](proxy/appmapping.md)
       * [Proxy Example](proxy/proxy_example.md)
   * [The Base Proxy Object](proxy/the_base_proxy_object.md)
   * [The Event Handlers](proxy/the_event_handlers.md)
       * [Distinguishing Request Types](proxy/distinguishing_request_types.md)
       * RenderData()
   * [Proxy Events](proxy/proxy_events.md)
   * [Ajax Data Binding & More](proxy/ajax_data_binding_&_more.md)
   * [Flex Integration](proxy/flex_integration.md)
   * [Standard Return Types](proxy/standard_return_types.md)
   * [Execution Profiler Monitor](proxy/execution_profiler_monitor.md)
   * [Caveats & Gotchas](proxy/caveats_&_gotchas.md)
   * [Conclusion](proxy/conclusion.md)
* [Layouts & Views](layouts_n_views_guide/index.md)
   * [Response Types](layouts_n_views_guide/response_types.md)
   * [Rendering Views](layouts_n_views_guide/rendering_views/index.md)
       * [Setting Views For Rendering](layouts_n_views_guide/rendering_views/setting_views_for_rendering.md)
       * [Implicit Views](layouts_n_views_guide/rendering_views/implicit_views.md)
       * [Views With No Layout](layouts_n_views_guide/rendering_views/views_with_no_layout.md)
       * [Views With Specific Layout](layouts_n_views_guide/rendering_views/views_with_specific_layout.md)
       * [Views From A Module](layouts_n_views_guide/rendering_views/views_from_a_module.md)
       * [View Caching](layouts_n_views_guide/rendering_views/view_caching.md)
       * [Handler Return Rendering](layouts_n_views_guide/rendering_views/handler_return_rendering.md)
       * [Render Nothing](layouts_n_views_guide/rendering_views/render_nothing.md)
       * [Inline Rendering](layouts_n_views_guide/rendering_views/inline_rendering.md)
       * [Content Variable Views](layouts_n_views_guide/rendering_views/content_variable_views.md)
       * [Rendering External Views](layouts_n_views_guide/rendering_views/rendering_external_views.md)
       * [Rendering With Local Variables](layouts_n_views_guide/rendering_views/rendering_with_local_variables.md)
       * [Rendering Collections](layouts_n_views_guide/rendering_views/rendering_collections.md)
       * [View Helpers](layouts_n_views_guide/rendering_views/view_helpers.md)
       * [View Events](layouts_n_views_guide/rendering_views/view_events.md)
   * [Layouts](layouts_n_views_guide/layouts/index.md)
       * [Basic Layouts](layouts_n_views_guide/layouts/basic_layouts.md)
       * [Nested Layouts](layouts_n_views_guide/layouts/nested_layouts.md)
       * [Default Layout](layouts_n_views_guide/layouts/default_layout.md)
   * [Layouts Helpers](layouts_n_views_guide/layouts_helpers.md)
   * [Overriding Layouts](layouts_n_views_guide/overriding_layouts.md)
   * [Implicit Layout/View Declarations](layouts_n_views_guide/implicit_layoutview_declarations/index.md)
       * [Layouts From A Module](layouts_n_views_guide/implicit_layoutview_declarations/layouts_from_a_module.md)
       * [Layout Events](layouts_n_views_guide/implicit_layoutview_declarations/layout_events.md)
   * [Rendering Data](layouts_n_views_guide/rendering_data.md)
       * [Global Parameters](layouts_n_views_guide/global_parameters.md)
       * [JSON Parameters](layouts_n_views_guide/json_parameters.md)
       * [XML Parameters](layouts_n_views_guide/xml_parameters.md)
       * [Renderdata With Formats](layouts_n_views_guide/renderdata_with_formats.md)
       * [Custom Data Conversion](layouts_n_views_guide/custom_data_conversion.md)
   * [Helpers UDF's](layouts_n_views_guide/helpers_udfs.md)
   * [Viewlets (Portable Events)](layouts_n_views_guide/viewlets_portable_events.md)
       * [Funky Viewlets](layouts_n_views_guide/funky_viewlets.md)
   * [Tips And Tricks](layouts_n_views_guide/tips_and_tricks.md)
* [Ajax Integration](ajax_integration/index.md)
   * [Returnint HTML](ajax_integration/returnint_html.md)
       * [Event Handler Return](ajax_integration/event_handler_return.md)
       * [Render HTML](ajax_integration/render_html.md)
       * [Layout+View](ajax_integration/layout+view.md)
   * [Returning DATA (XML/JSON/WDDX/ANY)](ajax_integration/returning_data_xmljsonwddxany.md)
       * [RenderData With Formats](ajax_integration/renderdata_with_formats.md)
   * [ColdBox Proxy](ajax_integration/coldbox_proxy.md)
       * [Techniques](ajax_integration/techniques.md)
   * [ColdBox Debugger](ajax_integration/coldbox_debugger.md)
* [Interceptors](interceptors/index.md)
   * [ForgeBox Interceptors](interceptors/forgebox_interceptors.md)
   * [Event Driven Programming](interceptors/event_driven_programming.md)
   * [Resources](interceptors/resources.md)
   * [For what can I use them](interceptors/for_what_can_i_use_them.md)
   * [How do they work?](interceptors/how_do_they_work.md)
       * [Conventions](interceptors/conventions.md)
       * [eventpattern annotation](interceptors/eventpattern_annotation.md)
   * [Interceptor Declaration](interceptors/interceptor_declaration.md)
       * [Configuration File](interceptors/configuration_file.md)
       * [Programmatically](interceptors/programmatically.md)
   * [Custom Events](interceptors/custom_events.md)
       * [Configuration Registration](interceptors/configuration_registration.md)
       * [Programmatic Registration](interceptors/programmatic_registration.md)
       * [Usage](interceptors/usage.md)
       * [Announcing Interceptions](interceptors/announcing_interceptions.md)
   * [Core Interception Points](interceptors/core_interception_points.md)
       * [Application Life Cycle](interceptors/application_life_cycle.md)
       * [Object Creating Events](interceptors/object_creating_events.md)
       * [Layout-View Events](interceptors/layout-view_events.md)
       * [Module Events](interceptors/module_events.md)
       * [Debugger Events](interceptors/debugger_events.md)
       * [ORM Events](interceptors/orm_events.md)
       * [CacheBox Events](interceptors/cachebox_events.md)
   * [Interceptor Output Buffer](interceptors/interceptor_output_buffer.md)
       * [Output Buffer Argument](interceptors/output_buffer_argument.md)
   * [Unregistering Interceptors](interceptors/unregistering_interceptors.md)
   * [Reporting Methods](interceptors/reporting_methods.md)
   * [Interceptor Asynchronicity](interceptors/interceptor_asynchronicity.md)
   * [Conclusion](interceptors/conclusion.md)
* [Controller Decorator](controller_decorator/index.md)
* [Flash RAM](flash_ram/index.md)
   * [Flash Storage](flash_ram/flash_storage.md)
   * [Using Flash RAM](flash_ram/using_flash_ram.md)
   * [Creating Your Own Flash Scope](flash_ram/creating_your_own_flash_scope.md)
   * [Summary](flash_ram/summary.md)
* [Recepies](recipes/index.md)
   * [Using Helper UDF's and CFC's](recipes/using_helper_udfs_and_cfcs.md)
   * [My First Event Handler](recipes/my_first_event_handler.md)
   * [My First Custom Exception Handler](recipes/my_first_custom_exception_handler.md)
   * [My First Custom Plugin](recipes/my_first_custom_plugin.md)
   * [My First Interceptor](recipes/my_first_interceptor.md)
   * [My First Context Decorator](recipes/my_first_context_decorator.md)
   * [How to time your code](recipes/how_to_time_your_code.md)
   * [Object factory custom plugin](recipes/object_factory_custom_plugin.md)
   * [Loading a custom ColdBox configuration file](recipes/loading_a_custom_coldbox_configuration_file.md)
   * [Tracing messages to the debug panel](recipes/tracing_messages_to_the_debug_panel.md)
   * [Creating a messagebox css](recipes/creating_a_messagebox_css.md)
   * [Creating a Custom exception template](recipes/creating_a_custom_exception_template.md)
   * [Caching objects](recipes/caching_objects.md)
   * [Creating a 404 template via onInvalidEvent](recipes/creating_a_404_template_via_oninvalidevent.md)
   * [Is there an easy, programmatic way to remove a specific element from the view cache](recepies/is_there_an_easy,_programmatic_way_to_remove_a_specific_element_from_the_view_cache.md)
   * [Building a simple Basic HTTP Authentication Interceptor](recipes/building_a_simple_basic_http_authentication_interceptor.md)
* [Runnable Code Examples](run/index.md)
