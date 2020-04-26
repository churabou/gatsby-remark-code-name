### Installation


clone it as local plugin

```
git clone https://github.com/churabou/gatsby-remark-code-name.git ~/{project-root}/plugins/
```

### Usage 


in gatsby-config.js

```
plugins: [
  {
    resolve: 'gatsby-transformer-remark',
    options: {
      plugins: [
        {
          resolve: 'gatsby-remark-code-name',
        }
      ]
    }
  }
]
```

in markdown

    # just add filename
    ``` index.js
       const a = 0;
    ```



### Style

``` .css
.gatsby-code-name {
  margin: 0px 0px -8px 0px;
  background: gray;
  color: white;
  padding: 4px;
}
```
