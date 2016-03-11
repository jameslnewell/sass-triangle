# sass-triangle

Mixin for creating CSS triangles.

## Installation

    npm install --save sass-triangle

## Usage

```scss
@import "sass-triangle";

.triangle-1 {
  @include triangle(up, 24px, $color: #ffe619); //3 almost equal length sides
}

.triangle-2 {
  @include triangle(right, 24px 10px, $color: #ffaf14); //2 equal sides
}

.triangle-3 {
  @include triangle(left, 24px 12px 0px, $color: #ff3005); //no equal sides
}

.triangle-4 {
  @include triangle(down, 16px, $color: #ff1870);
}

```
