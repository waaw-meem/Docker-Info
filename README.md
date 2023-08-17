# Docker-Info

<h2>What is Docker and Why do we use it?</h2>

<p>Docker is a container technology A tool for creating and managing containers </p>
<p>Container: A standardized unit of software. A package of Code and dependencies to run that code</p>

<h6>Main points</h6>
<ul>
  <li>The same container always yields the exact same "application and execution behavior!" No matter where or by whom it might be executed  </li>
  <li>Support for containers is built into modern Operating system</li>
  <li>Docker simplifies the creation and management of such containers</li>
</ul>

<h2>Virtual Machine / Virtual Operating System</h2>

<p>
Containers:

Isolation: Containers provide application-level isolation. Each container contains the application along with its dependencies and libraries, all sharing the same OS kernel. They are isolated from each other but share the host OS resources.

Resource Efficiency: Containers are lightweight and use fewer resources compared to VMs because they share the host OS kernel and don't require a full operating system per container.

Speed and Portability: Containers are quick to start and stop, making them great for rapid scaling and development. They are highly portable across different environments.

Density: You can run many containers on a single host machine due to their efficiency, making them suitable for microservices architecture.

Examples: Docker, Kubernetes, and container orchestration platforms.
</p>

<p>
  Virtual Machines (VMs):

Isolation: VMs provide full OS-level isolation. Each VM includes its own operating system instance and resources, which can be different from the host OS.

Resource Overhead: VMs are heavier in terms of resource consumption since each VM runs a separate OS instance.

Security: VMs offer stronger isolation between applications due to their separate OS instances.

Flexibility: VMs can run different operating systems on the same physical hardware, providing greater flexibility in terms of software compatibility.

Examples: VMware, Hyper-V, VirtualBox.
</p>


<h2>Docker Setup</h2>
<p></p>
