# Node Gallery CLI

A simple way to serve photos, similar to http-server.
This is just a small wrapper around node-gallery, it uses node-gallery for all the heavy lifting.

## Install

`npm install -g node-gallery-cli`

## Basic Usage

`node-gallery`

By default node-gallery-cli only listens on localhost:3000 and servers the current directory.

## Extended Usage

All args are optional

`node-gallery --port 3000 --ip 0.0.0.0 --title "My Awesome Photo Gallery" --dir="/path/to/awesome/photos/"`

## License

Copyright (C) 2016 [Brian Douglass](http://bhdouglass.com/)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3, as published
by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranties of MERCHANTABILITY, SATISFACTORY QUALITY, or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
