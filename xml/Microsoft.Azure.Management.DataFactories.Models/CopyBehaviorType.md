<Type Name="CopyBehaviorType" FullName="Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType">
  <TypeSignature Language="C#" Value="public class CopyBehaviorType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CopyBehaviorType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType" />
  <TypeSignature Language="VB.NET" Value="Public Class CopyBehaviorType" />
  <TypeSignature Language="F#" Value="type CopyBehaviorType = class" />
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
            <span data-ttu-id="52085-101">Alle verfügbaren Typen von Verhalten beim Kopieren.</span><span class="sxs-lookup"><span data-stu-id="52085-101">All available types of copy behavior.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CopyBehaviorType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FlattenHierarchy">
      <MemberSignature Language="C#" Value="public const string FlattenHierarchy;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string FlattenHierarchy" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.FlattenHierarchy" />
      <MemberSignature Language="VB.NET" Value="Public Const FlattenHierarchy As String " />
      <MemberSignature Language="F#" Value="val mutable FlattenHierarchy : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.FlattenHierarchy" />
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
            <span data-ttu-id="52085-102">Alle Dateien aus dem Quellordner werden in der ersten Ebene der Zielordner sein.</span><span class="sxs-lookup"><span data-stu-id="52085-102">All files from the source folder will be in the first level of target folder.</span></span> <span data-ttu-id="52085-103">Dies ist das Standardverhalten für BlobSink mit Binärdaten.</span><span class="sxs-lookup"><span data-stu-id="52085-103">This is the default behavior for blobSink with binary data.</span></span>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.BlobSink" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeFiles">
      <MemberSignature Language="C#" Value="public const string MergeFiles;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string MergeFiles" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.MergeFiles" />
      <MemberSignature Language="VB.NET" Value="Public Const MergeFiles As String " />
      <MemberSignature Language="F#" Value="val mutable MergeFiles : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.MergeFiles" />
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
            <span data-ttu-id="52085-104">Führen Sie alle Dateien aus dem Quellordner in eine Datei.</span><span class="sxs-lookup"><span data-stu-id="52085-104">Merge all files from the source folder into one file.</span></span> <span data-ttu-id="52085-105">Dies ist das Standardverhalten für BlobSink mit tabellarischen Daten.</span><span class="sxs-lookup"><span data-stu-id="52085-105">This is the default behavior for blobSink with tabular data.</span></span>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.BlobSink" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveHierarchy">
      <MemberSignature Language="C#" Value="public const string PreserveHierarchy;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string PreserveHierarchy" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.PreserveHierarchy" />
      <MemberSignature Language="VB.NET" Value="Public Const PreserveHierarchy As String " />
      <MemberSignature Language="F#" Value="val mutable PreserveHierarchy : string" Usage="Microsoft.Azure.Management.DataFactories.Models.CopyBehaviorType.PreserveHierarchy" />
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
            <span data-ttu-id="52085-106">Erhaltung der Dateihierarchie im Ordner "Ziel".</span><span class="sxs-lookup"><span data-stu-id="52085-106">Preserve the file hierarchy in the target folder.</span></span> <span data-ttu-id="52085-107">Dies ist das Standardverhalten für FileSystemSink.</span><span class="sxs-lookup"><span data-stu-id="52085-107">This is the default behavior for FileSystemSink.</span></span>
            <see cref="T:Microsoft.Azure.Management.DataFactories.Models.FileSystemSink" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>