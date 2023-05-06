# glutin-tao

The crate provides cross-platform glutin `Display` bootstrapping with tao.

This crate is also a reference on how to do the bootstrapping of glutin when
used with a cross-platform windowing library.



## Updating

````bash
git checkout upstream-master
git pull
git subtree split --prefix=glutin-winit --onto upstream-glutin-winit -b upstream-glutin-winit
git checkout main
git rebase upstream-glutin-winit
````

