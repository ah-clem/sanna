# xanna
A prototype assigned names and numbers authority.

## contents
The top-level directory contains a prototype web site with documentation and a registry placeholder.  Below, this directory is sometimes refered to as "site".

The prototype is based on setting up an "assigned names and numbers authority": xANNA. Replace the "x" depending what needs names and numbers assigned.  Certificates are just one type of assigned name.  Other artifacts such as MIB's, or protocol numbers, or whatever can be published in the registry.

The "site" directory can be served by a web server.  The top-level has a "index.html" file as a navigation entry point.  Other pages cover authentication, registry layout, the certificate authority, etc.  This end-user documentation is useful to the publisher as well: reading and customizing the contents will be big help getting started running your own CA.

The registry itself is contained within "site".  However, the registry does not depend on the site web contents at all: it can be replicated someplace else without the site web pages furnished here.

## usage
The envisioned usage of this project is the following:

1. Someone wanting to set up a CA and/or ANNA, forks the repo.
2. The "site" content is edited (including changing the name "xANNA" to something else) according to needs.
3. The edited site is published.
4. The registry is published along with the site and/or detached from the site.

## see also
The [ranger6/ca](https://github.com/ranger6/ca) repo contains tools for running a CA, including publishing to the registry structure described here.  These tools do not need to be present when publishing the site.

The xANNA repo is meant to be forked, edited, published, and maintained as described above.  You then have your own ANNA.

On the other hand, the "ca" repo containing tools and docs should be shared open source with folks making contributions and pulling down improvements.
