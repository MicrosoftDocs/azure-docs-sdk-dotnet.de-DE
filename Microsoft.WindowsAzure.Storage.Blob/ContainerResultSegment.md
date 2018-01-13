<Type Name="ContainerResultSegment" FullName="Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment">
  <TypeSignature Language="C#" Value="public class ContainerResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ContainerResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public Class ContainerResultSegment" />
  <TypeSignature Language="F#" Value="type ContainerResultSegment = class" />
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
            Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> führt und enthält fortsetzungs-und Paginierungsinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As BlobContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> Ergebnisse.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobContinuationToken" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of CloudBlobContainer)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;" Usage="Microsoft.WindowsAzure.Storage.Blob.ContainerResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> Ergebnisse.
            </summary>
        <value>Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Blob.CloudBlobContainer" /> Objekte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>