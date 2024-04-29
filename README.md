# rustNX
A rust implementation of a [PKNX4](https://nxformat.github.io/) format reader.

### Features
- [x] Tree-like iteration on nodes
- [x] String Nodes
- [x] Long and Double
- [x] Vectors node
- [x] Audio Nodes (Without data, just the info)
- [x] Bitmap nodes (Without data, just the info)

For the meantime, i have no intention of implementing the Audio and Bitmap nodes, since there's no use for them when developing a server. Maybe ill add them.... who knows.

### TODO
- [x] Fix and clean borrows, what a pain
- [ ] Make a Better Test
- [ ] Make a benchmark test
- [ ] Optimize and clean code
- [ ] Audio Nodes (With data)
- [ ] Bitmap nodes (With Data)