<Type Name="QueueResultSegment" FullName="Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment">
  <TypeSignature Language="C#" Value="public sealed class QueueResultSegment" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit QueueResultSegment extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class QueueResultSegment" />
  <TypeSignature Language="F#" Value="type QueueResultSegment = class" />
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
            Stellt ein Segment dar <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> -Ergebnissen mit fortsetzungsinformationen für paginierungsszenarien.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken ContinuationToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContinuationToken As QueueContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" Usage="Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Fortsetzungstoken zum Abrufen des nächsten Segments von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> Ergebnisse. Gibt null zurück, wenn keine weiteren Ergebnisse vorhanden sind.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; Results { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.Results" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Results As IEnumerable(Of CloudQueue)" />
      <MemberSignature Language="F#" Value="member this.Results : seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;" Usage="Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> Ergebnisse.
            </summary>
        <value>Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> Objekte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>