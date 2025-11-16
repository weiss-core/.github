# WEISS – Web EPICS Interface & Synoptic Studio

**WEISS** is a no-code, drag-and-drop tool for creating EPICS web operation interfaces.  
The system is built to be **intuitive, responsive, and user friendly**, allowing quick design and
usage of control panels.

## Why should you use web?

- **Client-side rendering**: most processing happens in the browser, drastically reducing server RAM
  and compute requirements.
- **Ease of access**: users can open the interface from any browser without installing specialized
  tools or relying on remote desktop sessions Access control remains simple to enforce through
  standard mechanisms such as network restrictions, authentication and reverse proxies.
- **Built for scale**: web deployment allows multiple users to access the system simultaneously
  without dedicated virtual machines or remote desktops.
- **Extensive community support**: web technologies have one of the largest developer ecosystems,
  offering libraries, tools, and best practices far beyond the scientific environment.
- **Integration friendly**: easy to connect with authentication systems (LDAP), version control
  (GitHub/GitLab), and other modern tools.

---

## Key Features

- **No-code, drag-and-drop interface**: rapidly create web operator panels without touching HTML or
  JS.
- **Fully featured editor**: Use standard editor tools like widget alignment, grid snapping, layers
  management, widget grouping and others via keyboard shortcuts or mouse interaction.
- **Live EPICS PV communication**: supports both Channel Access (CA) and PV Access (PVA) protocols
  via modern implementations.
- **Runtime vs edit mode**: instantly start and stop communication with a switch button.
- **Extensible widget library**: ready-to-use components for common controls and displays, others
  can be easily created.
- **Responsive and intuitive design** : A considerable effort was put into user experience and
  making things intuitive.
- **Portable file format (JSON)**: All OPIs can be exported or imported using straightforward JSON
  files. Easily create or edit OPIs programatically as you will.

Follow the app development and mapped improvements on
[WEISS Project Dashboard](https://github.com/orgs/weiss-core/projects/1/).
