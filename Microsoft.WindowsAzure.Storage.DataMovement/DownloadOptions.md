<Type Name="DownloadOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions">
  <TypeSignature Language="C#" Value="public sealed class DownloadOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DownloadOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DownloadOptions" />
  <TypeSignature Language="F#" Value="type DownloadOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3139f-101">Stellt eine Reihe von Optionen, die für den Downloadvorgang angegeben werden können</span><span class="sxs-lookup"><span data-stu-id="3139f-101">Represents a set of options that may be specified for download operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public bool DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.DisableContentMD5Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3139f-102">Ruft ab oder legt ein Flag, das angibt, ob die Content-MD5 oder beim Lesen nicht von Daten aus dem Quellobjekt zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="3139f-102">Gets or sets a flag that indicates whether to validate content MD5 or not when reading data from the source object.</span></span>
            <span data-ttu-id="3139f-103">Wenn es sich bei festlegen auf "true", "Quellobjekt Content MD5 überprüft wird; Andernfalls wird Quellinhalt MD5-Objekt nicht überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="3139f-103">If set to true, source object content MD5 will be validated; otherwise, source object content MD5 will not be validated.</span></span>
            <span data-ttu-id="3139f-104">Wenn nicht angegeben ist, wird standardmäßig auf "false".</span><span class="sxs-lookup"><span data-stu-id="3139f-104">If not specified, it defaults to false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAccessCondition">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AccessCondition SourceAccessCondition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.AccessCondition SourceAccessCondition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.SourceAccessCondition" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAccessCondition As AccessCondition" />
      <MemberSignature Language="F#" Value="member this.SourceAccessCondition : Microsoft.WindowsAzure.Storage.AccessCondition with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadOptions.SourceAccessCondition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AccessCondition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3139f-105">Ruft ab oder legt ein <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> -Objekt, das die zugriffsbedingungen für das Quellobjekt darstellt.</span><span class="sxs-lookup"><span data-stu-id="3139f-105">Gets or sets an <see cref="T:Microsoft.WindowsAzure.Storage.AccessCondition" /> object that represents the access conditions for the source object.</span></span> <span data-ttu-id="3139f-106">Wenn <c>null</c>, keine Bedingung verwendet.</span><span class="sxs-lookup"><span data-stu-id="3139f-106">If <c>null</c>, no condition is used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>