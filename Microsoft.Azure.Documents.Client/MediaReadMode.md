<Type Name="MediaReadMode" FullName="Microsoft.Azure.Documents.Client.MediaReadMode">
  <TypeSignature Language="C#" Value="public enum MediaReadMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MediaReadMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Client.MediaReadMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum MediaReadMode" />
  <TypeSignature Language="F#" Value="type MediaReadMode = " />
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
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary> 
            Gibt den Modus für die Verwendung beim Herunterladen von Inhalt Anlage (auch als) Medien) im Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Buffered">
      <MemberSignature Language="C#" Value="Buffered" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.MediaReadMode Buffered = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.MediaReadMode.Buffered" />
      <MemberSignature Language="VB.NET" Value="Buffered" />
      <MemberSignature Language="F#" Value="Buffered = 0" Usage="Microsoft.Azure.Documents.Client.MediaReadMode.Buffered" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Client.MediaReadMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Inhalt wird an den Client gepuffert, und nicht direkt aus dem Inhaltsspeicher gestreamt. Verwenden Sie gepufferte reduzieren die Zeit zum Lesen und Schreiben von Mediendateien.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Streamed">
      <MemberSignature Language="C#" Value="Streamed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Documents.Client.MediaReadMode Streamed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Documents.Client.MediaReadMode.Streamed" />
      <MemberSignature Language="VB.NET" Value="Streamed" />
      <MemberSignature Language="F#" Value="Streamed = 1" Usage="Microsoft.Azure.Documents.Client.MediaReadMode.Streamed" />
      <MemberType>Field</MemberType>
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
        <ReturnType>Microsoft.Azure.Documents.Client.MediaReadMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Inhalt wird direkt aus dem Inhaltsspeicher gestreamt, ohne Pufferung auf dem Client. Verwenden Sie Streamed reduzieren den Speicherbedarf Client lesen und Schreiben von Mediendateien.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>