---
title: li-bundled-documents
type: metadata-plugins
menus:
  reference:
    parent: Metadata Plugins
summary: A list of documents belonging to a bundle.
support:
  document: true
  media: false
  tableDashboard: false
  include: false
  displayFilter: false
  dynamicIndexing: true
  systemMetadata: true
  planningSystem: true
description: |
  Used for managing bundles of documents.
defaultUI: None
storageFormat: |
  {
    $ref: 'documents',
    references: [
      {
        id: <String>
      }
    ]
  }
contentTypeConfig: |2
        handle: 'myHandle'
        type: 'li-bundled-documents'
---