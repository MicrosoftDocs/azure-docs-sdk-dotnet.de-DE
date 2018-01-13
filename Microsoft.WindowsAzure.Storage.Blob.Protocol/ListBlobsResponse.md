<Type Name="ListBlobsResponse" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse">
  <TypeSignature Language="C#" Value="public sealed class ListBlobsResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListBlobsResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListBlobsResponse&#xA;Inherits ResponseParsingBase(Of IListBlobEntry)" />
  <TypeSignature Language="F#" Value="type ListBlobsResponse = class&#xA;    inherit ResponseParsingBase&lt;IListBlobEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Methoden zum Analysieren der Antwort Blob-Auflistungsvorgang bereit.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListBlobsResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream">Der Stream, der analysiert werden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blobs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; Blobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; Blobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Blobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Blobs As IEnumerable(Of IListBlobEntry)" />
      <MemberSignature Language="F#" Value="member this.Blobs : seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Blobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" /> aus der Antwort.
            </summary>
        <value>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public string Delimiter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Delimiter As String" />
      <MemberSignature Language="F#" Value="member this.Delimiter : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Trennzeichen-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.
            </summary>
        <value>Eine Zeichenfolge mit den Trennzeichen-Wert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As BlobListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Kontext für die Auflistung aus der XML-Antwort ab.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.BlobListingContext" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Marker-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.
            </summary>
        <value>Eine Zeichenfolge mit den markerwert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den "maxresults"-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.
            </summary>
        <value>Eine ganze Zahl, die mit dem Wert "maxresults".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.NextMarker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den NextMarker-Wert aus der XML-Antwort, wenn die Auflistung nicht abgeschlossen war.
            </summary>
        <value>Eine Zeichenfolge, die den NextMarker-Wert enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of IListBlobEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;" Usage="listBlobsResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Analysiert das Antwort-XML für ein Blob-Auflistungsvorgang an.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.IListBlobEntry" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.ListBlobsResponse.Prefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Präfix Wertanbieter für die Auflistungsvorgang aus der XML-Antwort ab.
            </summary>
        <value>Eine Zeichenfolge, die mit dem Präfix-Wert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>