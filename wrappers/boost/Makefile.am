pyexec_LTLIBRARIES= libwebqqboost.la
libwebqqboost_la_SOURCES= libwebqqboost.cpp
libwebqqboost_la_LDFAGS= 
libwebqqboost_la_CPPFLAGS=-I../../jsoncpp/include -I/usr/include/python2.7/ -I../../src  $(CURL_CFLAGS) 

AM_CPPFLAGS= 
AM_CXXFLAGS = -fPIC -ggdb -O0  -Wall -DUSE_EVENT_QUEUE
AM_LDFLAGS =  $(CURL_LIBS) -lpython2.7 -lboost_python-2.7  -L../../src/.libs/ -lwebqq
