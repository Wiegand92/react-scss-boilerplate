# React with Sass and Webpack

## About

This is my personal boilerplate for Webpack using Sass and React. I will try to keep this up to date as I learn more about all of the tools!

## Other Dependencies

  To be succinct these all make babel play nice with both webpack and react, I will re-research and update specific reasoning for each one.

  - "@babel/core"
  - "@babel/plugin-proposal-class-properties"
  - "@babel/preset-env"
  - "@babel/preset-react"
  - "babel-loader"

  This keeps your public/scripts folder clean between builds if you need to split code

  - "clean-webpack-plugin"

  This provides a standardized way to declare NODE_ENV between systems

  - "cross-env"

  Inlines styles when in production mode

  - "css-loader"
  - "style-loader"
  
  When you build this extracts the css to a separate file

  - "mini-css-extract-plugin"
  
  CLI for sass

  - "sass"
  
  Processes sass for webpack

  - "sass-loader"
  
  Source Maps!

  - "source-map-loader"
  
  A stylesheet to normalize styles
  - "modern-normalize"