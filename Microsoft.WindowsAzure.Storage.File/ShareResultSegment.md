<Type Name="ShareResultSegment" FullName="Microsoft.WindowsAzure.Storage.File.ShareResultSegment">
  <TypeSignature Language="C#" Value="public class ShareResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ShareResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.ShareResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public Class ShareResultSegment" />
  <TypeSignature Language="F#" Value="type ShareResultSegment = class" />
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
            Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> führt und enthält fortsetzungs-und Paginierungsinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.ShareResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As FileContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.File.FileContinuationToken" Usage="Microsoft.WindowsAzure.Storage.File.ShareResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Objekt, mit dem Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> Ergebnisse.
            </summary>
        <value>Das Fortsetzungstoken.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.ShareResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of CloudFileShare)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="Microsoft.WindowsAzure.Storage.File.ShareResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> Ergebnisse.
            </summary>
        <value>Eine aufzählbare Auflistung von Ergebnissen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>