Turning an Angular application

into a server side rendered Angular application

or an Angular application

that's ready for server side rendering

is as simple as running NG add @Angular/ssr.

ng add @angular/ssr

below code run on browser after all componnet hsa sbeene render in next cycle

afterNextRender(()=> {
      const tasks = localStorage.getItem('tasks');

    if (tasks) {
      this.tasks.set(JSON.parse(tasks));
    }
       
    });

    some issue fix later 

