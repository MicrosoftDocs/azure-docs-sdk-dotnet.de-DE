<Type Name="RetryInfo" FullName="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo">
  <TypeSignature Language="C#" Value="public sealed class RetryInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RetryInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RetryInfo" />
  <TypeSignature Language="F#" Value="type RetryInfo = class" />
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
            <span data-ttu-id="bf953-101">Gibt Parameter für die nächste Wiederholung einer Anforderung für die Microsoft Azure-Speicherdienste, einschließlich Zielspeicherort und Positionsmodus für die nächste Wiederholung sowie Intervall bis zur nächsten Wiederholung vorgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="bf953-101">Specifies parameters for the next retry of a request to be made against the Microsoft Azure storage services, including the target location and location mode for the next retry and the interval until the next retry.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf953-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf953-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RetryInfo (Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext retryContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.#ctor(Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo : Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext -&gt; Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" Usage="new Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo retryContext" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryContext" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" />
      </Parameters>
      <Docs>
        <param name="retryContext"><span data-ttu-id="bf953-103">Die <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> -Objekt, das an die wiederholungsrichtlinie übergeben wurde.</span><span class="sxs-lookup"><span data-stu-id="bf953-103">The <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryContext" /> object that was passed in to the retry policy.</span></span></param>
        <summary>
            <span data-ttu-id="bf953-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bf953-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public TimeSpan RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan RetryInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : TimeSpan with get, set" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf953-105">Ruft das Intervall bis zur nächsten Wiederholung ab.</span><span class="sxs-lookup"><span data-stu-id="bf953-105">Gets the interval until the next retry.</span></span>
            </summary>
        <value><span data-ttu-id="bf953-106">Ein <see cref="T:System.TimeSpan" /> Objekt, das das Intervall bis zur nächsten Wiederholung angibt.</span><span class="sxs-lookup"><span data-stu-id="bf953-106">A <see cref="T:System.TimeSpan" /> object specifying the interval until the next retry.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetLocation">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.StorageLocation TargetLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.TargetLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetLocation As StorageLocation" />
      <MemberSignature Language="F#" Value="member this.TargetLocation : Microsoft.WindowsAzure.Storage.StorageLocation with get, set" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.TargetLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf953-107">Ruft ab oder legt den Zielspeicherort für die nächste Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="bf953-107">Gets or sets the target location for the next retry.</span></span>
            </summary>
        <value><span data-ttu-id="bf953-108">Ein <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="bf953-108">A <see cref="T:Microsoft.WindowsAzure.Storage.StorageLocation" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="retryInfo.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bf953-109">Gibt eine Zeichenfolge zurück, die die aktuelle <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" />-Instanz darstellt.</span><span class="sxs-lookup"><span data-stu-id="bf953-109">Returns a string that represents the current <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> instance.</span></span>
            </summary>
        <returns><span data-ttu-id="bf953-110">Eine Zeichenfolge, die für die aktuelle <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> Instanz.</span><span class="sxs-lookup"><span data-stu-id="bf953-110">A string that represents the current <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatedLocationMode">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode UpdatedLocationMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode UpdatedLocationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.UpdatedLocationMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdatedLocationMode As LocationMode" />
      <MemberSignature Language="F#" Value="member this.UpdatedLocationMode : Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode with get, set" Usage="Microsoft.WindowsAzure.Storage.RetryPolicies.RetryInfo.UpdatedLocationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bf953-111">Ruft ab oder legt den Positionsmodus für nachfolgende Wiederholungen fest.</span><span class="sxs-lookup"><span data-stu-id="bf953-111">Gets or sets the location mode for subsequent retries.</span></span>
            </summary>
        <value><span data-ttu-id="bf953-112">Ein <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" />-Enumerationswert.</span><span class="sxs-lookup"><span data-stu-id="bf953-112">A <see cref="T:Microsoft.WindowsAzure.Storage.RetryPolicies.LocationMode" /> enumeration value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>