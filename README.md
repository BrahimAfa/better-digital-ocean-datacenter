# better-digital-ocean-datacenter
Calculates average ping metric for different digitalocean's datacenters

## How to use

```curl
curl -s https://raw.githubusercontent.com/BrahimAfa/better-digital-ocean-datacenter/master/test-datacenter.sh > test-datacenter.sh
```bash

$ chmod +x test-datacenter.sh
$ ./test-datacenter.sh <ping_count>
```
{

### Arguments

`<ping_count>`: Amount of ping requests performed (default = 1)

## License

The MIT License (MIT)

Copyright (c) 2016 Bruno Cascio <brunocascio@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
