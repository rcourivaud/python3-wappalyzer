# python3-wappalyzer
=================

change the project name into wappalyzer after git clone


Python driver for [Wappalyzer][], a web application
detection utility.

    >>> from wappalyzer import Wappalyzer, WebPage
    >>> wappalyzer = Wappalyzer.latest()
    >>> webpage = WebPage.new_from_url('http://example.com')
    >>> wappalyzer.analyze(webpage)
    set([u'EdgeCast'])
or 

    >>> from wappalyzer import Wappalyzer, WebPage
    >>> wappalyzer = Wappalyzer.latest()
    >>> webpage = WebPage.new_from_response(response) #here you can provide a requests response object
    >>> apps = wappalyzer.analyze(webpage) 
     set([u'EdgeCast'])
     
[Wappalyzer]: http://wappalyzer.com/