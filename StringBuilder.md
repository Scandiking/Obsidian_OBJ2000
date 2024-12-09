java.lang.Object
	java.lang.StringBuilder

A mutable sequence of characters. This class provides an API compatible with [[StringBuffer]], but with no guarantee of synchronization. Tis class is designed for use as a drop-in replacement for `StringBuffer` in places where the string buffer was being used by a single thread (as is generally the case). Where possible, it is recommended that this class be used in preference to `StringBuffer` as it will be faster under most implementations.