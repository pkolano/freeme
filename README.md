Filtering and Reorganization of Excessive E-Mail Emanation (FreeMe)
===================================================================

FreeMe is a tool for reducing e-mail clutter while highlighting messages
of interest.  In particular, FreeMe was designed for large HPC
environments, in which there are many thousands of interacting
components that experience failures asynchronously.  During large-scale
outages, administrators may receive overwhelming numbers of similar
e-mails that may cause e-mails of unrelated failures to get lost in the
shuffle and never resolved.

FreeMe allows each administrator to manage their own individual
subscriptions with the ability to match full regular expressions against
any e-mail field, providing fine-grained filtering.  E-mails can either
be processed as they are received in procmail-like fashion or read from
an existing inbox.  Options include ignoring uninteresting messages,
having messages be resent on demand, or having them sent in a
consolidated digest format, which dramatically reduces the number of
messages received.  Original e-mails are kept in a historical archive
that can be queried on demand.  FreeMe can also be used in a
single-user configuration.

FreeMe is in active production at the NASA Advanced Supercomputing
Facility.

For installation details, see "INSTALL".  For usage details, see
"freeme.1" (in man page format, viewable with "nroff -man").  For
license details, see "COPYING".

Questions, comments, fixes, and/or enhancements welcome.

--Paul Kolano <pkolano@gmail.com>

