sa-swagger-editor
=================

[![Build Status](https://travis-ci.org/softasap/sa-swagger-editor.svg?branch=master)](https://travis-ci.org/softasap/sa-swagger-editor)

Swagger UI is a dependency-free collection of HTML, Javascript, and CSS assets that dynamically generate beautiful documentation and sandbox from a Swagger-compliant API. Because Swagger UI has no dependencies, you can host it in any server environment, or on your local machine
Swagger Editor - is a web based editor you can use to edit and preview service yml files

Example of usage (all parameters are optional)

Simple

  roles:
    - {
        role: "sa-swagger-editor"
      }


Advanced:


  roles:
    - {
        role: "sa-swagger-editor",
        install_dir: "/home/slavko/apps/swagger_editor",

        option_install_nodejs: true,
        nodejs_version: "4.x"

      }




