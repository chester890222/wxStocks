![wxStocks](/wxStocks_logo.png?raw=true "wxStocks")

This program is now in beta, but i'm still happy to accept any pull requests or suggestions if you want to help out.

Disclaimer: This program comes as is, and probably has some errors in it. This software should not be used as financial advice or financial analysis, it is for educational use only. Consult a financial advisor before, after, and even while using this software. Double check any calculations done by this software, and review all the code for errors before using. By using this software you release the author(s) from any liability regarding the use of this software. Please don't sue me. Sorry about the massive disclaimer, but finance programs are fairly litigious business.

wxStocks is a investment analysis program that could help teach you to scrape, screen, sort, and prepare a portfolio for learning about buying and selling equities.

Built using wx as its framework (specifically wxPython3.0-osx-cocoa-py2.7), and pyql as its scraping tool.

*NOTE: El Capitan has broken wxPython on Mac indefinitely. The bug is here: http://trac.wxwidgets.org/ticket/17203 and it's been 7 months since any update. I'll be resuming develpment on Windows 10 and Linux Mint, which should actually help with many of the display issues on those.

Requirements: Python 2.X, [wxPython](http://www.wxpython.org), [NumPy](http://www.numpy.org)

Nonessential but recommended: [python cryptography](https://cryptography.io/en/latest/), [xlrd](https://pypi.python.org/pypi/xlrd)

License: [AGPL](https://en.wikipedia.org/wiki/Affero_General_Public_License)

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Installation:

Python:

If you are running a mac or linux Python 2.X. To check, open your terminal and just type "python", which should lead to a prompt that looks like ">>>". You can then quit by typing "quit()". If that doesn't work, go here: https://www.python.org/downloads/

If you are running windows, i've found it's better to install 64-bit python if you're on a 64-bit processor for this program, go here and install python 2.X, ideally the latest release: https://www.python.org/downloads/

wxPython:

http://www.wxpython.org/download.php

Note: I built this using the cocoa build for OSX. I should work on all other builds though, but i've heard some of my friends are having problems while using ipython. Not sure what to do if you're having issue, this is a tough one. Generally though, for Windows or Linux: $ pip install wxpython

Numpy:

$ pip install numpy

http://docs.scipy.org/doc/numpy/user/install.html

Python cryptography library (not required):

$ pip install cryptography

xlrd:

$ pip install xlrd
https://pypi.python.org/pypi/xlrd

Screenshots:

OS X (Yosemite)
![Portfolios](/wxStocks_portfolio.png?raw=true "Portfolios")
![Custom Analysis](/wxStocks_custom_analysis.png?raw=true "Custom Analysis")
![Sale Prep](/wxStocks_sale_prep.png?raw=true "Sale Prep")

Linux (Mint)
![Linux](/wxStocks_linux.png?raw=true "Linux")

Windows (10)
![Windows](/wxStocks_windows.png?raw=true "Windows")
