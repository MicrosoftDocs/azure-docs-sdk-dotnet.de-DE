<Type Name="ImageStoreContentResult" FullName="System.Fabric.Query.ImageStoreContentResult">
  <TypeSignature Language="C#" Value="public sealed class ImageStoreContentResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ImageStoreContentResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.ImageStoreContentResult" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ImageStoreContentResult" />
  <TypeSignature Language="F#" Value="type ImageStoreContentResult = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine ImageStoreContentResult enthält Informationen zu Store Bildinhalt, die zurückgegebene Liste Inhaltsabfrage
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="StoreFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.ImageStoreFileInfo&gt; StoreFiles { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ImageStoreFileInfo&gt; StoreFiles" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ImageStoreContentResult.StoreFiles" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreFiles As IList(Of ImageStoreFileInfo)" />
      <MemberSignature Language="F#" Value="member this.StoreFiles : System.Collections.Generic.IList&lt;System.Fabric.Query.ImageStoreFileInfo&gt;" Usage="System.Fabric.Query.ImageStoreContentResult.StoreFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.ImageStoreFileInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der Image Store Dateien ab.</para>
        </summary>
        <value>
          <para>Die Liste der Images SSDL-Dateien.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreFolders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.ImageStoreFolderInfo&gt; StoreFolders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.ImageStoreFolderInfo&gt; StoreFolders" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.ImageStoreContentResult.StoreFolders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreFolders As IList(Of ImageStoreFolderInfo)" />
      <MemberSignature Language="F#" Value="member this.StoreFolders : System.Collections.Generic.IList&lt;System.Fabric.Query.ImageStoreFolderInfo&gt;" Usage="System.Fabric.Query.ImageStoreContentResult.StoreFolders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.ImageStoreFolderInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der Image Store-Ordner.</para>
        </summary>
        <value>
          <para>Die Liste der Image Store-Ordner.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>