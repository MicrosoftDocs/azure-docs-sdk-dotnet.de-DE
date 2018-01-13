<Type Name="UploadSessionInfo" FullName="System.Fabric.Query.UploadSessionInfo">
  <TypeSignature Language="C#" Value="public sealed class UploadSessionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UploadSessionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.UploadSessionInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UploadSessionInfo" />
  <TypeSignature Language="F#" Value="type UploadSessionInfo = class" />
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
            Enthält Informationen über die Image Store hochladen-Sitzung
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExpectedRanges">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.UploadChunkRange[] ExpectedRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.UploadChunkRange[] ExpectedRanges" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.ExpectedRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpectedRanges As UploadChunkRange()" />
      <MemberSignature Language="F#" Value="member this.ExpectedRanges : System.Fabric.Query.UploadChunkRange[]" Usage="System.Fabric.Query.UploadSessionInfo.ExpectedRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.UploadChunkRange[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen des Bereichs der Datei hochladen, die nicht empfangen wurde.</para>
        </summary>
        <value>
          <para>Der Bereich des Hochladens der Datei, die nicht empfangen wurde.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileSize">
      <MemberSignature Language="C#" Value="public long FileSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FileSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.FileSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileSize As Long" />
      <MemberSignature Language="F#" Value="member this.FileSize : int64" Usage="System.Fabric.Query.UploadSessionInfo.FileSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Größe der Image Store-Datei in Bytes ab.</para>
        </summary>
        <value>
          <para>Die Größe in Bytes der Image Store-Datei.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ModifiedDate">
      <MemberSignature Language="C#" Value="public DateTime ModifiedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ModifiedDate" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.ModifiedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ModifiedDate As DateTime" />
      <MemberSignature Language="F#" Value="member this.ModifiedDate : DateTime" Usage="System.Fabric.Query.UploadSessionInfo.ModifiedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft das Datum und die Uhrzeit der letzten die Datei Änderung.</para>
        </summary>
        <value>
          <para>Das Datum und Uhrzeit der letzten die Datei Änderung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public Guid SessionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid SessionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SessionId As Guid" />
      <MemberSignature Language="F#" Value="member this.SessionId : Guid" Usage="System.Fabric.Query.UploadSessionInfo.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die ID der Sitzung hochladen.</para>
        </summary>
        <value>
          <para>Der Upload-Sitzungs-ID.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreRelativePath">
      <MemberSignature Language="C#" Value="public string StoreRelativePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreRelativePath" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.UploadSessionInfo.StoreRelativePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreRelativePath As String" />
      <MemberSignature Language="F#" Value="member this.StoreRelativePath : string" Usage="System.Fabric.Query.UploadSessionInfo.StoreRelativePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Abrufen des relativen Pfads der Datei aus dem systemeigenen Image Store Stamm.</para>
        </summary>
        <value>
          <para>Der relative Pfad der Datei aus dem systemeigenen Image speichern Stamm.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>