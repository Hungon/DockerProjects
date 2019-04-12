<h1> DockerProjects</h1>
<p>I'm going to walk through it to learn docker.</p>

<h3>hello-world-java</h3>
<p>This project is my first java application using docker.</p>
<li>To build this image</li>
<code><p>$ docker build -f Dockerfile -t sample/hello-world-java:1 .</P></code>
<li>To compile this app</li>
<code><p>$ docker run --rm -v $PWD:/app -w /app sample/hello-world-java:1 javac Main.java</p></code>
<li>To run this app</li>
<code><p>$ docker run --rm -v $PWD:/app -w /app sample/hello-world-java:1 java Main</p></code>

<h3>hello-world-python</h3>
<p>This project is my first python application using docker.</p>
<p>Nagigate top-level directory you created and type following command if you want to try this app.</p>
<li>To run this app</li>
<code><p>$ docker-compose up</p></code>
<li>To close this app</li>
<code><p>$ docker-compose down</p></code>
