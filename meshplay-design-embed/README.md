# Meshplay Design Embed Package

Meshplay Design Embedding allows you to export a design in a format that can be integrated into websites, blogs, or platforms supporting HTML, CSS, and JavaScript. This embedded version offers an interactive representation of the design, simplifying sharing with infrastructure stakeholders.
  
## meshplay-design-embed react component

This component is meant to facilate the usage of meshplay embeddings inside react and its frameworks

Usage :
```
import MeshplayDesignEmbed from '@khulnasoft/meshplay-design-embed'


function Design() {
  return (
    <>

      <div>
        <MeshplayDesignEmbed
          embedScriptSrc="embedded-design-embed1.js"
          embedId="embedded-design-a3d3f26e-4366-44e6-b211-1ba4e1a3e644"
        />
      </div>
    </>
  );
}

```

Props:
 - embedScriptSrc: "Relative path to the exported design"
 - embedId: "Emebedded design id"
 - style: "Custom styles to the embeded design E.g. backgroundColor, textColor, etc"

### Limitations

Certain aspects of Meshplay Designs and their visualization are not currently supported in embed mode (when a design is embedded into a webpage).

1. Relationship: Singular Node inventory wallet (badge)
1. Relationship: TagSets (BubbleSets)
1. Component: Textboxes
1. Function: Error badges based on validation checks
1. Function: Component Locking (pinning a component in-place moving with edges; Automove)
1. Function: Viewing component configuration
1. Function: Viewing comments 

Learn more about [embedding Meshplay Designs](https://docs.khulnasoft.com/meshmap/designer/embedding-designs/).
