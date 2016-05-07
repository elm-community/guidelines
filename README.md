# elm-community

## tl;dr 

A community dedicated to sharing maintaince of Elm packages.

## Process

- If a repo is proposed to be moved to elm-community, we must assign a maintainer to that repo. 
- The maintainer will have full support to merge PRs as they seem fit.
- Other community members can ping the maintainer if they want something to get merged.
- If there's something that really needs to get merged, and the maintainer has taken more than 7 days to respond, we can merge things without their invovlement. 
- Unresponsive champions will be emailed. Lack of response will mean a new maintainer will be assigned to that repo.


## Further info

This is a meta-repository for organizational stuff related to elm-community.
The idea is that we can use the 'issues' to discuss organzational questions,
and we can use this file (README.md) to document organizational things.
(Eventually, we may want to link with other documents, or use the 'wiki'
feature, but starting with a simple README seems reasonable).

* [Mandate](#mandate)
    * [The role of a maintainer](#the-role-of-a-maintainer)
    * [Package Maintenance](#package-maintenance)
    * [Community-driven Documentation](#community-driven-documentation)
* [Getting involved](#getting-involved)
    * [Issues and pull requests](#issues-and-pull-requests)
    * [Become a maintainer](#become-a-maintainer)
    * [Owners](#owners)

## Mandate

The idea behind elm-community is to have a shared, unofficial home for certain
kinds of collaborative Elm-related work.

Now, why might that be useful? Without something like elm-community, work is
either located within the core of [elm-lang](https://github.com/elm-lang), or it 
is located in individual (or corporate) accounts. So, elm-community is a kind
of "middle ground" between those two.

So, why might such a middle ground be useful? So far, we've identified two areas:
package maintenance and community-driven documentation.

### The role of a maintainer

A maintainer is expected to:

- Be friendly at all times when dealing with issues and pull requests. Aggressiveness is not needed.
- Be responsive and take no longer than 7 days to respond to an issue. It's okay to be slow! If you know you will be slow, ping someone else in elm-community and ask them to help out by reviewing.
- Lead the direction of a repository. As a champion, you will need to make calls on API design. Don't let packages come to elm-community to die.

### Package Maintenance

It sometimes happens that packages which are widely used need a bit of
maintenance -- for instance, to accommodate changes in Elm, or for other
reasons. Normally, package authors will deal with that themselves, of course,
possibly with the help of pull requests from interested community members etc.
However, sometimes package authors may not be available, for one reason or
another, and other work can be blocked until the maintenance is performed.

In such cases, it is certainly possible for some individual to fork the
package, do the necessary maintenance, and publish it themselves -- and we do
not wish to discourage that. However, there may be cases where people don't
want to take on the implicit obligations involved in maintaining a published
package -- and yet, it needs to be done.

In those cases, elm-community can provide a home for a fork, and the necessary
work to maintain the package.

Here are a few principles we might follow in this area:

1. If you think there is a package that should be adopted here, feel free to
   open an issue in this repository. (And, to repeat, this is not to discourage
   you from adopting a package yourself, if you want to take that on).

2. For the most part, we don't expect to do innovative work on packages here.
   That is, to the extent that innovative new features can be added to a
   package, that should mostly be done in people's individual accounts. What
   we'll do here is mostly maintenance. However, there may be some exceptions,
   in cases where there are good reasons to do innovative work here.

### Community-driven Documentation

Elm has great documentation, but there is always room for more, and room for
documentation oriented towards particular audiences. Now, people can write
documentation on their own, but that can be a bit of a daunting prospect.
Plus, ultimately, documentation needs to be published, or integrated somewhere,
so some kind of central location is useful. So, this can serve as a central
point for that.


## Getting Involved

So, suppose you'd like to get involved in elm-community. What can you do?

### Issues and pull requests

We welcome issues and pull requests, in the usual way. That is, you can create
an issue if you have a request or see a problem. Or, you can fork anything
here, make some changes, and send a pull request.

### Become a maintainer

Open a PR against [maintainers.md](maintainers.md) adding your email and Github username. 

### Owners

For your information, the 'owner' of elm-community (in Github terms) is
@rgrempel. So, feel free to contact me if there are things that need to be
done that require an 'owner'.
