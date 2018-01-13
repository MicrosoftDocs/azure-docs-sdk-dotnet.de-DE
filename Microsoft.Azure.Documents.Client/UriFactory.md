<Type Name="UriFactory" FullName="Microsoft.Azure.Documents.Client.UriFactory">
  <TypeSignature Language="C#" Value="public static class UriFactory" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UriFactory extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.UriFactory" />
  <TypeSignature Language="VB.NET" Value="Public Class UriFactory" />
  <TypeSignature Language="F#" Value="type UriFactory = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Hilfsklasse, die beim Erstellen der verschiedenen Uris unterstützen benötigt für die Verwendung mit der Instanz DocumentClient im Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>To be added.</remarks>
    <example>
            Im folgenden Beispiel UriFactory verwendet, um eine DocumentCollectionLink zu erstellen und dann zum Erstellen eines Dokuments verwendet.
            <code language="c#"><![CDATA[ 
            Uri collUri = UriFactory.CreateDocumentCollectionUri("MyDb", "MyCollection");
            var doc = await client.CreateDocumentAsync(collUri, new {id = "MyDoc"});
            ]]></code></example>
  </Docs>
  <Members>
    <Member MemberName="CreateAttachmentUri">
      <MemberSignature Language="C#" Value="public static Uri CreateAttachmentUri (string databaseId, string collectionId, string documentId, string attachmentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateAttachmentUri(string databaseId, string collectionId, string documentId, string attachmentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateAttachmentUri(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateAttachmentUri (databaseId As String, collectionId As String, documentId As String, attachmentId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateAttachmentUri : string * string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateAttachmentUri (databaseId, collectionId, documentId, attachmentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
        <Parameter Name="attachmentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <param name="documentId">Der Dokument-id</param>
        <param name="attachmentId">Die Attachment-id</param>
        <summary>
            Erhält eine Datenbank, die Sammlung, die Dokument und die Anlage-Id, wird hierdurch einen Anlagenlink erstellt.
            </summary>
        <returns>
            Eine Anlagenlink im Format /dbs/ {0} / colls / \ {1\} / Dokumente / \ {2\} / Anlagen / \ {3\} mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" />, \ {2\} wird die <paramref name="documentId" /> und \ {3\} wird<paramref name="attachmentId" /></returns>
        <remarks>Wird verwendet werden, wenn beim Ersetzen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.Attachment" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateCollectionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateCollectionUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateCollectionUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateCollectionUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateCollectionUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateCollectionUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateCollectionUri (databaseId, collectionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("CreateCollectionUri method is deprecated, please use CreateDocumentCollectionUri method instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <summary>
            Wenn Sie eine Datenbank und Sammlung-Id, wird hierdurch einen Link der Auflistung erstellt.
            </summary>
        <returns>
            Eine Auflistung Link im Format /dbs/ {0} / colls / \ {1\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von den <paramref name="databaseId" /> und \ {1\}<paramref name="collectionId" /></returns>
        <remarks>Verwendet werden würde, beim Aktualisieren oder Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, erstellen eine <see cref="T:Microsoft.Azure.Documents.Document" />, eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, eine <see cref="T:Microsoft.Azure.Documents.Trigger" />, eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, oder beim Ausführen einer Abfrage mit CreateDocumentQuery in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateConflictUri">
      <MemberSignature Language="C#" Value="public static Uri CreateConflictUri (string databaseId, string collectionId, string conflictId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateConflictUri(string databaseId, string collectionId, string conflictId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateConflictUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateConflictUri (databaseId As String, collectionId As String, conflictId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateConflictUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateConflictUri (databaseId, collectionId, conflictId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="conflictId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <param name="conflictId">Die Id des Konflikt</param>
        <summary>
            Wenn eine Datenbank, der Auflistung und der Konflikt-Id, wird hierdurch einen Konflikt Link erstellt.
            </summary>
        <returns>
            Ein Konflikt Link im Format /dbs/ {0} / colls / \ {1\} / Konflikte / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="conflictId" /></returns>
        <remarks>Wird beim Erstellen einer <see cref="T:Microsoft.Azure.Documents.Conflict" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDatabaseUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDatabaseUri (string databaseId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDatabaseUri(string databaseId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDatabaseUri(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDatabaseUri (databaseId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDatabaseUri : string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDatabaseUri databaseId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <summary>
            Wenn Sie eine Datenbank-Id, wird hierdurch einen datenbanklink erstellt.
            </summary>
        <returns>
            Ein datenbanklink in das Format der /dbs/ {0} / mit {0} wird von einem Uri mit Escapezeichen versehen Version der<paramref name="databaseId" /></returns>
        <remarks>Wird verwendet werden, wenn das Erstellen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" /> oder ein <see cref="T:Microsoft.Azure.Documents.User" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentCollectionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDocumentCollectionUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDocumentCollectionUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentCollectionUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDocumentCollectionUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDocumentCollectionUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentCollectionUri (databaseId, collectionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <summary>
            Wenn Sie eine Datenbank und Sammlung-Id, wird hierdurch einen Link der Auflistung erstellt.
            </summary>
        <returns>
            Eine Auflistung Link im Format /dbs/ {0} / colls / \ {1\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von den <paramref name="databaseId" /> und \ {1\}<paramref name="collectionId" /></returns>
        <remarks>Verwendet werden würde, beim Aktualisieren oder Löschen einer <see cref="T:Microsoft.Azure.Documents.DocumentCollection" />, erstellen eine <see cref="T:Microsoft.Azure.Documents.Document" />, eine <see cref="T:Microsoft.Azure.Documents.StoredProcedure" />, eine <see cref="T:Microsoft.Azure.Documents.Trigger" />, eine <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" />, oder beim Ausführen einer Abfrage mit CreateDocumentQuery in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateDocumentUri">
      <MemberSignature Language="C#" Value="public static Uri CreateDocumentUri (string databaseId, string collectionId, string documentId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateDocumentUri(string databaseId, string collectionId, string documentId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDocumentUri (databaseId As String, collectionId As String, documentId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateDocumentUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateDocumentUri (databaseId, collectionId, documentId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="documentId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <param name="documentId">Der Dokument-id</param>
        <summary>
            Wenn eine Datenbank, die Sammlung und den Dokument-Id, wird hierdurch Link zu einem Dokument erstellt.
            </summary>
        <returns>
            Link zu einem Dokument in das Format der /dbs/ {0} / colls / \ {1\} / Dokumente / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="documentId" /></returns>
        <remarks>Verwendet werden würde, beim Erstellen einer <see cref="T:Microsoft.Azure.Documents.Attachment" />, oder beim Ersetzen oder Löschen von einer <see cref="T:Microsoft.Azure.Documents.Document" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreatePartitionKeyRangesUri">
      <MemberSignature Language="C#" Value="public static Uri CreatePartitionKeyRangesUri (string databaseId, string collectionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreatePartitionKeyRangesUri(string databaseId, string collectionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreatePartitionKeyRangesUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreatePartitionKeyRangesUri (databaseId As String, collectionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreatePartitionKeyRangesUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreatePartitionKeyRangesUri (databaseId, collectionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <summary>
            Eine Datenbank und die Sammlung erstellt, dies einen Partition Schlüsselbereichen Link im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>
            Partitionsschlüssel Bereiche Link im Format /dbs/ {0} / colls / \ {1\} / Pkranges mit {0} wird von einem Uri mit Escapezeichen versehen Version der <paramref name="databaseId" /> und \ {1\} wird <paramref name="collectionId" />.
            </returns>
        <remarks>To be added.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreatePermissionUri">
      <MemberSignature Language="C#" Value="public static Uri CreatePermissionUri (string databaseId, string userId, string permissionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreatePermissionUri(string databaseId, string userId, string permissionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreatePermissionUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreatePermissionUri (databaseId As String, userId As String, permissionId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreatePermissionUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreatePermissionUri (databaseId, userId, permissionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="permissionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="userId">Die Benutzer-id</param>
        <param name="permissionId">Die Id der Berechtigung</param>
        <summary>
            Wenn Sie einen Datenbank und die Benutzer-Id, wird hierdurch eine Berechtigung Verknüpfung erstellt.
            </summary>
        <returns>
            Eine Berechtigung Verknüpfung im Format /dbs/ {0} / Benutzer / \ {1\} / Berechtigungen / \ {2\} mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="userId" /> und \ {2\}<paramref name="permissionId" /></returns>
        <remarks>Würde verwendet werden, beim Ersetzen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.Permission" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateStoredProcedureUri">
      <MemberSignature Language="C#" Value="public static Uri CreateStoredProcedureUri (string databaseId, string collectionId, string storedProcedureId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateStoredProcedureUri(string databaseId, string collectionId, string storedProcedureId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateStoredProcedureUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateStoredProcedureUri (databaseId As String, collectionId As String, storedProcedureId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateStoredProcedureUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateStoredProcedureUri (databaseId, collectionId, storedProcedureId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="storedProcedureId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <param name="storedProcedureId">Id der gespeicherten Prozedur</param>
        <summary>
            Wenn eine Datenbank, die Sammlung und die gespeicherte Prozedur-Id, wird hierdurch einen gespeicherte Prozedur Link erstellt.
            </summary>
        <returns>
            Eine gespeicherte Prozedur Link im Format /dbs/ {0} / colls / \ {1\} / Sprocs / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="storedProcedureId" /></returns>
        <remarks>Wird verwendet werden, wenn ersetzen, ausführen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.StoredProcedure" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateTriggerUri">
      <MemberSignature Language="C#" Value="public static Uri CreateTriggerUri (string databaseId, string collectionId, string triggerId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateTriggerUri(string databaseId, string collectionId, string triggerId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateTriggerUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateTriggerUri (databaseId As String, collectionId As String, triggerId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateTriggerUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateTriggerUri (databaseId, collectionId, triggerId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="triggerId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <param name="triggerId">Trigger-id</param>
        <summary>
            Wenn eine Datenbank, die Sammlung und die Trigger-Id, wird hierdurch eine Verknüpfung Trigger erstellt.
            </summary>
        <returns>
            Ein Trigger Link im Format /dbs/ {0} / colls / \ {1\} / Triggers / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="triggerId" /></returns>
        <remarks>Wird verwendet werden, wenn ersetzen, ausführen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.Trigger" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateUserDefinedFunctionUri">
      <MemberSignature Language="C#" Value="public static Uri CreateUserDefinedFunctionUri (string databaseId, string collectionId, string udfId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateUserDefinedFunctionUri(string databaseId, string collectionId, string udfId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateUserDefinedFunctionUri(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUserDefinedFunctionUri (databaseId As String, collectionId As String, udfId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateUserDefinedFunctionUri : string * string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateUserDefinedFunctionUri (databaseId, collectionId, udfId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="collectionId" Type="System.String" />
        <Parameter Name="udfId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="collectionId">Die Sammlungs-id</param>
        <param name="udfId">Die Udf-id</param>
        <summary>
            Wenn eine Datenbank, die Sammlung und die Udf-Id, wird hierdurch einen Udf-Link erstellt.
            </summary>
        <returns>
            Ein Udf-Link in das Format der /dbs/ {0} / colls / \ {1\} / UDF / \ {2\} / mit {0} wird von einem Uri mit Escapezeichen versehen-Version von der <paramref name="databaseId" />, \ {1\} wird <paramref name="collectionId" /> und \ {2\} wird die<paramref name="udfId" /></returns>
        <remarks>Wird verwendet werden, wenn ersetzen, ausführen oder Löschen einer <see cref="T:Microsoft.Azure.Documents.UserDefinedFunction" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
    <Member MemberName="CreateUserUri">
      <MemberSignature Language="C#" Value="public static Uri CreateUserUri (string databaseId, string userId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Uri CreateUserUri(string databaseId, string userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Client.UriFactory.CreateUserUri(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateUserUri (databaseId As String, userId As String) As Uri" />
      <MemberSignature Language="F#" Value="static member CreateUserUri : string * string -&gt; Uri" Usage="Microsoft.Azure.Documents.Client.UriFactory.CreateUserUri (databaseId, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="databaseId" Type="System.String" />
        <Parameter Name="userId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="databaseId">Die Datenbank-id</param>
        <param name="userId">Die Benutzer-id</param>
        <summary>
            Wenn Sie einen Datenbank und die Benutzer-Id, wird hierdurch einen benutzerlink erstellt.
            </summary>
        <returns>
            Einen benutzerlink im Format /dbs/ {0} / Benutzer / \ {1\} / mit {0} wird eine Uri mit Escapezeichen versehen Version der <paramref name="databaseId" /> und \ {1\}<paramref name="userId" /></returns>
        <remarks>Würde verwendet werden, für die Erstellung einer <see cref="T:Microsoft.Azure.Documents.Permission" />, oder beim Ersetzen oder Löschen von einer <see cref="T:Microsoft.Azure.Documents.User" /> in Azure-Cosmos-Datenbank.</remarks>
        <altmember cref="M:System.Uri.EscapeUriString(System.String)" />
      </Docs>
    </Member>
  </Members>
</Type>