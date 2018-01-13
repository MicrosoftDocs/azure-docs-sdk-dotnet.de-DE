<Type Name="AzureSearchIndexWriteBehavior" FullName="Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior">
  <TypeSignature Language="C#" Value="public static class AzureSearchIndexWriteBehavior" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AzureSearchIndexWriteBehavior extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSearchIndexWriteBehavior" />
  <TypeSignature Language="F#" Value="type AzureSearchIndexWriteBehavior = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Schreiben Sie das Verhalten, wenn Upserting in einen Azure Search-Index Dokumente.
            Eine Eigenschaft des <see cref="T:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexSink" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public const string Merge;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Merge" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Merge" />
      <MemberSignature Language="VB.NET" Value="Public Const Merge As String " />
      <MemberSignature Language="F#" Value="val mutable Merge : string" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Merge" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Merge aktualisiert ein vorhandenes Dokument mit den angegebenen Feldern. Alle in einer Zusammenführung angegebene Feld ersetzt das vorhandene Feld im Dokument. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Upload">
      <MemberSignature Language="C#" Value="public const string Upload;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string Upload" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Upload" />
      <MemberSignature Language="VB.NET" Value="Public Const Upload As String " />
      <MemberSignature Language="F#" Value="val mutable Upload : string" Usage="Microsoft.Azure.Management.DataFactories.Models.AzureSearchIndexWriteBehavior.Upload" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Dokument wird eingefügt werden, wenn sie neu ist und aktualisiert/ersetzt, falls vorhanden. Wenn ein Update ausgeführt wird, werden alle Felder ersetzt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>