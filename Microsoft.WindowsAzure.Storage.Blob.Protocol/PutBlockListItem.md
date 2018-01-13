<Type Name="PutBlockListItem" FullName="Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem">
  <TypeSignature Language="C#" Value="public sealed class PutBlockListItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PutBlockListItem extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PutBlockListItem" />
  <TypeSignature Language="F#" Value="type PutBlockListItem = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen Block in einer Blockliste dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PutBlockListItem (string id, Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode searchMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode searchMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.#ctor(System.String,Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (id As String, searchMode As BlockSearchMode)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem : string * Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode -&gt; Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" Usage="new Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem (id, searchMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="searchMode" Type="Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode" />
      </Parameters>
      <Docs>
        <param name="id">Die Block-ID.</param>
        <param name="searchMode">Einer der Enumerationswerte, der angibt, in welcher Block aufgelistet, für den Block gesucht werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.Id" />
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
            Ruft die Block-ID.
            </summary>
        <value>Die Block-ID.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchMode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode SearchMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode SearchMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.SearchMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchMode As BlockSearchMode" />
      <MemberSignature Language="F#" Value="member this.SearchMode : Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode" Usage="Microsoft.WindowsAzure.Storage.Blob.Protocol.PutBlockListItem.SearchMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlockSearchMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einen Wert, der angibt, welche Blocklisten nach dem Block durchsucht.
            </summary>
        <value>Einer der Enumerationswerte, der angibt, in welcher Block aufgelistet, für den Block gesucht werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>