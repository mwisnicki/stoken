FROM fedora:latest

RUN yum groupinstall -y "Development Tools"
RUN yum install -y git autoconf automake libtool

# For perl language server in vscode
RUN yum install -y cpan
RUN cpan Perl::LanguageServer

# For win32 development
RUN yum install -y mingw32-gnutls mingw32-libxml2 mingw32-gtk3
