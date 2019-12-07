# OHIF Viewers

- [Our Process](our-process.md)
- [Getting Started](getting-started.md)
- Essentials
  - [Installation](essentials/installation.md)
  - [Data Source](essentials/data-source.md)
  - [Configuration](essentials/configuration.md)
  - [Translating](essentials/translating.md)
  - [Troubleshooting](essentials/troubleshooting.md)
- [Contributing](contributing/index.md)
  - [Continuous Integration](continous-integration.md)

---

- [Architecture](architecture/index.md)
- [Viewer](viewer/index.md)
  - [Configuration](viewer/configuration.md)
  - [Themeing](viewer/themeing.md)
- [Extensions](extensions/index.md)
  - [Registering](extensions/index.md#registering-an-extension)
  - [Lifecycle Hooks](extensions/index.md#lifecycle-hooks)
    - [preRegistration](extensions/lifecycle/pre-registration.md)
  - [Modules](extensions/index.md#modules)
    - [Commands](extensions/modules/commands.md)
    - [Panel](extensions/modules/panel.md)
    - [SOP Class Handler](extensions/modules/sop-class-handler.md)
    - [Toolbar](extensions/modules/toolbar.md)
    - [Viewport](extensions/modules/viewport.md)
  - [Contexts](extension/index.md#contexts)
  - [OHIF Maintained](extension/index.md#maintained-extensions)
- [Services](services/index.md)
  - [Default](services/default/index.md)
    - [Measurements](services/default/measurements.md)
  - [UI](services/ui/index.md)
    - [Dialog Service](services/ui/ui-dialog-service.md)
    - [Modal Service](services/ui/ui-modal-service.md)
    - [Notification Service](services/ui/ui-notification-service.md)

---

- [Deployment](deployment/index.md)
  - [Embedded](deployment/index.md#embedded-viewer)
  - [Stand-alone](deployment/index.md#stand-alone-viewer)
  - [Data](deployment/index.md#data)
- Recipes
  - Script Include
    - [Embedding the Viewer](deployment/recipes/embedded-viewer.md)
  - Stand-Alone
    - [Build for Production](deployment/recipes/build-for-production.md)
    - [Static](deployment/recipes/static-assets.md)
    - [Nginx + Image Archive](deployment/recipes/nginx--image-archive.md)
    - [User Account Control](deployment/recipes/user-account-control.md)
    - [Google Cloud Healthcare](connecting-to-image-archives/google-cloud-healthcare.md)

---

- [FAQ](frequently-asked-questions.md)
- [Scope of Project](scope-of-project.md)
- [Browser Support](browser-support.md)
- [Help](help.md)