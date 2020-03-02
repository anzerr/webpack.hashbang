
### `Intro`
remove hashbang from file start

#### `Install`
``` bash
npm install --save git+https://git@github.com/anzerr/webpack.hashbang.git
```

### `Example`
``` javascript
{
    test: /\.js$/,
    use: 'webpack.hashbang'
}
```