# UV Template

cookiecutter を使った python 用のテンプレート

## Quickstart

- install cookiecutter

    ```
    pip install cookiecutter
    ```

- project の作成 
    1. project root directory ごと作成する場合

        ```
        cookiecutter https://github.com/osushinekotan/uv-template.git
        ```
    
    2. 作成済みの project root directory を使いたい場合 (clone した repository など)

        ```
        cd {project_dir}
        cookiecutter https://github.com/osushinekotan/uv-template.git -f -o ../
        ```

        - `project_slug` と `{projet_dir}` が同じ名前であり、それを上書きする形で template を作成する
        - cookicutter の [CL options](https://cookiecutter.readthedocs.io/en/1.7.0/advanced/cli_options.html) を使う
