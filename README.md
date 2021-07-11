# These settings were set by the catalyst build script that automatically
# built this stage.
# Please consult /usr/share/portage/config/make.conf.example for a more
# detailed example.
COMMON_FLAGS="-march=native -O2 -pipe"
CFLAGS="${COMMON_FLAGS}"
CXXFLAGS="${COMMON_FLAGS}"
FCFLAGS="${COMMON_FLAGS}"
FFLAGS="${COMMON_FLAGS}"

# NOTE: This stage was built with the bindist Use flag enabled
PORTDIR="/var/db/repos/gentoo"
DISTDIR="/var/cache/distfiles"
PKGDIR="/var/cache/binpkgs"

# This sets the language of build output to English.
# Please keep this setting intact when reporting bugs.
LC_MESSAGES=C

GRUB_PLATFORMS="efi-64"
USE="X a52 aac acl acpi alsa amd64 berkdb bluetooth branding bzip2 cairo \
     cdda cdr cli crypt cups dbus dri dts elogind emboss encode \
     exif flac fortran gdbm gif gles2 -gpm gtk gui iconv icu ipv6 \
     jpeg lcms libglvnd libnotify libtirpc mad matroska mng mp3 mp4 \
     ncurses networkmanager nls nptl ogg opengl openmp pango pcre \
     pdf png policykit pulseaudio python3_9 readline screencast \
     seccomp split-usr ssl svg tcpd truetype unicode upower usb \
     vorbis wav wayland wxwidgets x264 xattr xcb xml xv xvid zlib \
     examples"
MAKEOPTS="-j4"
ACCEPT_LICENSE="*"
LINGUAS="es"
L10N="es"
VIDEO_CARDS="i915 i965 intel nouveau vesa virtualbox"
INPUT_DEVICES="elographics evdev joysticks libinput vmmouse void synaptics wacom"
EMERGE_DEFAULT_OPTS="${EMERGE_DEFAULT_OPTS} --quiet-build=y"
ABI_X86="32 64"



