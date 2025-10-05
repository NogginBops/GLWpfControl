### 3.3.1
    * Sign the GLWpfControl assembly (@ChristianRadloff).
    * Allow software rendering fallback to support remote desktop. (@gmurray81)
    * Add D3DCREATE_FPU_PRESERVE to fix issue where creating a GLWpfControl caused double precision calculations to be done with single precision in 32-bit applications. (@NogginBops)

### 3.3.0
    * Add NonReloadingTabControl.
    * Add example with new NonReloadingTabControl.


### 3.2.3
    * Fix resizing
    * Unseal GLWpfControl
    * Fix crash on framebuffer access before inits

### 3.2.2
    * Fix for resource deallocation issue

### 3.2.1
    * Fix crash due to context mangling in tabbed views

### 3.2.0
    * Full backport & sync of all changes from 4.x.
    * Greatly improved backend
    * All memory leaks removed
    * Faster loading
    * Faster resizing
    * Less memory usage
    * Reduced duplicate rendering
    * New design time preview
    * Fixed crash when initialized inside a tab control
    * Simpler examples

### 3.1.0
    * Add support for non-continuous event-based rendering via InvalidateVisual().
    * Fix Incorrect minor version in OpenGL Settings.

### 3.0.1
    * Fix SharpDX.Direct3D9 dependency.

### 3.0.0
    * >10x performance increase via DirectX interop. Huge thanks to @Zcore.
    * Simplified API
    * Removed software render path
    * Added automatic context sharing by default

### 2.1.0
	* Allow support for external contexts across multiple controls.

### 2.0.3
    * Improve fix for event-ordering crash on some systems.

### 2.0.2
    * Possible fix for event-ordering crash on some systems.

### 2.0.1
    * Fix resize events not being raised.

### 2.0.0
    * Moved namespace to OpenTK.Wpf.
    * GLWpfControl now extends FrameworkElement instead of Control.
    * Moved to pure-code solution for greater simplicity.
    * Added some extra-paranoid null checking.
    
### 1.1.2
    * Possible fix for NPE on renderer access.

### 1.1.1
    * Automatically set the viewport for the user.

### 1.1.0
    * Use own HWND for improved performance (Thanks to @Eschryn)
    * Add time delta to the render event.
    * Better handling of resizing via delayed updates.
    * Remove slow-path detection (2x performance on low-end devices!)
    * Fix duplicate OpenGL resource unloading.
    
### 1.0.1
    * Add API to access the control's framebuffer.

### 1.0.0
	* Initial release

