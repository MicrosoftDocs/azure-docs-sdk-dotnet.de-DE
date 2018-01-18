<Type Name="TransferConfigurations" FullName="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations">
  <TypeSignature Language="C#" Value="public class TransferConfigurations" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TransferConfigurations extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" />
  <TypeSignature Language="VB.NET" Value="Public Class TransferConfigurations" />
  <TypeSignature Language="F#" Value="type TransferConfigurations = class" />
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
            <span data-ttu-id="ff069-101">TransferConfigurations-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ff069-101">TransferConfigurations class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TransferConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ff069-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ff069-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlockSize">
      <MemberSignature Language="C#" Value="public int BlockSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 BlockSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberSignature Language="VB.NET" Value="Public Property BlockSize As Integer" />
      <MemberSignature Language="F#" Value="member this.BlockSize : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.BlockSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff069-103">Ruft ab oder legt die Blockgröße zum Windows Azure-Speicher übertragen zu gehörte blockiert.</span><span class="sxs-lookup"><span data-stu-id="ff069-103">Gets or sets the BlockSize to use for Windows Azure Storage transfers to block blob(s).</span></span> <span data-ttu-id="ff069-104">Es muss zwischen 4MB und 100MB und werden mehrere 4 MB.</span><span class="sxs-lookup"><span data-stu-id="ff069-104">It must be between 4MB and 100MB and be multiple of 4MB.</span></span>
            
            <span data-ttu-id="ff069-105">Derzeit ist die Anzahl der max-Block eines Block-BLOBs auf 50000 beschränkt.</span><span class="sxs-lookup"><span data-stu-id="ff069-105">Currently, the max block count of a block blob is limited to 50000.</span></span>
            <span data-ttu-id="ff069-106">Beim Übertragen einer großen Datei und die Blockgröße bereitgestellt ist kleiner als der Mindestwert - (Größe/50000), es muss zurückgesetzt werden auf einen Wert größer als der Minimalwert und mehrere 4 MB für diese Datei.</span><span class="sxs-lookup"><span data-stu-id="ff069-106">When transfering a big file and the BlockSize provided is smaller than the minimum value - (size/50000), it'll be reset to a value which is greater than the minimum value and multiple of 4MB for this file.</span></span>
            </summary>
        <value><span data-ttu-id="ff069-107">BlockSize zum Windows Azure-Speicher übertragen zu können.</span><span class="sxs-lookup"><span data-stu-id="ff069-107">BlockSize to use for Windows Azure Storage transfers.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParallelOperations">
      <MemberSignature Language="C#" Value="public int ParallelOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ParallelOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property ParallelOperations As Integer" />
      <MemberSignature Language="F#" Value="member this.ParallelOperations : int with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.ParallelOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff069-108">Ruft ab oder legt ihn fest Elemente aus ein Wert, der angibt, wie viele arbeiten, die gleichzeitig verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="ff069-108">Gets or sets a value indicating how many work items to process concurrently.</span></span> <span data-ttu-id="ff069-109">Herunterladen oder Hochladen von ein einzelnes Blob kann eine große Anzahl von Arbeitsaufgaben bestehen.</span><span class="sxs-lookup"><span data-stu-id="ff069-109">Downloading or uploading a single blob can consist of a large number of work items.</span></span>
            </summary>
        <value><span data-ttu-id="ff069-110">Wie viele Arbeitsaufgaben gleichzeitig verarbeiten.</span><span class="sxs-lookup"><span data-stu-id="ff069-110">How many work items to process concurrently.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAgentPrefix">
      <MemberSignature Language="C#" Value="public string UserAgentPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserAgentPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAgentPrefix As String" />
      <MemberSignature Language="F#" Value="member this.UserAgentPrefix : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.TransferConfigurations.UserAgentPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ff069-111">Ruft ab oder legt die Benutzer-Agent-Präfix</span><span class="sxs-lookup"><span data-stu-id="ff069-111">Gets or sets the user agent prefix</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>