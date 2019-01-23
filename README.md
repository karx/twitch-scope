# Twitch-scope
Control, Broadcast and Analyse the telescope stream using Twitch 

## Modules 

*   On scope module, to interface with telescope
    
*   Telescope stream module, which accepts the feed from telescope and streams to Web

*   Twitch modules, to expose option, to viewers by which they can interact with the telescope.

*   Cloud functions, to run compute on the streams, eg Detect count of 'flashes of light'


## Scope module
Most astronomical hardware now come with a built-in system with computer control and geo-locator*.

For 
* Telescopes with Only Motorized mount
    For these we can use Rasperry pi to add computer aided control
    List :

    *   To be added


* Telescopes with built-in system
    Also, commandsets to interact with these are also available, which can be used to interface.
    List:

    * To be added


## Stream module
We use OBS to stream the telescope feed to Twitch Channel

## Twitch modules
* Chat Interaction Module
    * Operations mode: Track Celstrial object or Free roam
    * Options to choose celestrial object to focus next on
    * Options/Directions to move/control the telescope remotely

## Compute Functions
These are AWS lambda functions which can be triggered by simple APIs which take, stream identifier, start time and end time.


