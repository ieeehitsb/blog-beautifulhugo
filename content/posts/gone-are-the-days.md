+++
date = 2020-07-31T14:06:00Z
title = "Gone are the Days!"

+++
**Lorem Ipsum** is simply dummied text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.

    root.add(animation);
    console.clear();
    window.onload = () => {
    const root = new THREERoot();
    root.renderer.setClearColor(0xffffff);
    root.camera.position.set(0, 0, -120);
    // root.controls.autoRotate = true;
    
      let light;
    
      light = new THREE.DirectionalLight();
      light.position.set(0, 1, 0);
      root.add(light);
    
      light = new THREE.DirectionalLight();
      light.position.set(0, -1, 0);
      root.add(light);
    
      const animation = new Animation();
      root.add(animation);