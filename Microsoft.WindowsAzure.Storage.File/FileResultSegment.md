<Type Name="FileResultSegment" FullName="Microsoft.WindowsAzure.Storage.File.FileResultSegment">
  <TypeSignature Language="C#" Value="public sealed class FileResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FileResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.FileResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FileResultSegment" />
  <TypeSignature Language="F#" Value="type FileResultSegment = class" />
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
            Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> -Ergebnissen mit fortsetzungsinformationen für paginierungsszenarien.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As FileContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.File.FileContinuationToken" Usage="Microsoft.WindowsAzure.Storage.File.FileResultSegment.ContinuationToken" />
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
            Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> Ergebnisse. Gibt <c>null</c> , wenn keine weiteren Ergebnisse vorhanden sind.
            </summary>
        <value>Das Fortsetzungstoken.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.IListFileItem&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.FileResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of IListFileItem)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;" Usage="Microsoft.WindowsAzure.Storage.File.FileResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.IListFileItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.IListFileItem" /> Ergebnisse.
            </summary>
        <value>Eine aufzählbare Auflistung von Ergebnissen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>