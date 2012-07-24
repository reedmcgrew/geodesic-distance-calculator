# Geodesic Distance Calculator

This calculator only currently works when the NSEW directionality on both latitudes and on both longitudes match.  For example, pairs (30.1N,75.6E) and (30.4N,70.2E) should yield an approximately correct result, but (30.1N,75.6E) and (30.4N,70.2W) will not.

This implementation uses the Halversine central angle formula and outputs results in standard miles.



THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS
IN THE SOFTWARE.

Copyright 2012 by Reed McGrew under the MIT License
