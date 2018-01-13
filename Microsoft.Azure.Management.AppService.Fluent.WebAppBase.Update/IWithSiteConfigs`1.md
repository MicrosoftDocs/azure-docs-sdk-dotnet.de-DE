<Type Name="IWithSiteConfigs&lt;FluentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs&lt;FluentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSiteConfigs&lt;FluentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSiteConfigs`1&lt;FluentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSiteConfigs(Of FluentT)" />
  <TypeSignature Language="F#" Value="type IWithSiteConfigs&lt;'FluentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="FluentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="FluentT"><span data-ttu-id="a5566-101">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="a5566-101">The type of the resource.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a5566-102">Die Phase des Web app-Updates, sodass andere Konfigurationen festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="a5566-102">The stage of the web app update allowing other configurations to be set.</span></span> <span data-ttu-id="a5566-103">Diese Konfigurationen können geklont werden, beim Erstellen oder mit einem bereitstellungsslot ausgetauscht wurde.</span><span class="sxs-lookup"><span data-stu-id="a5566-103">These configurations can be cloned when creating or swapping with a deployment slot.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAutoSwapSlotName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithAutoSwapSlotName (string slotName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithAutoSwapSlotName(string slotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithAutoSwapSlotName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAutoSwapSlotName (slotName As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAutoSwapSlotName : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithAutoSwapSlotName slotName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="slotName"><span data-ttu-id="a5566-104">Der Name der Slot oder "Produktion" an die automatischen-Austausch.</span><span class="sxs-lookup"><span data-stu-id="a5566-104">The name of the slot, or 'production', to auto-swap.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-105">Der slotname zum automatischen-Austausch gibt an, wenn eine Bereitstellung in die Web-app abgeschlossen ist / bereitstellungsslot.</span><span class="sxs-lookup"><span data-stu-id="a5566-105">Specifies the slot name to auto-swap when a deployment is completed in this web app / deployment slot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-106">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-106">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDefaultDocument">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithDefaultDocument (string document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithDefaultDocument(string document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithDefaultDocument(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultDocument (document As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultDocument : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithDefaultDocument document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="a5566-107">Standard-Dokument.</span><span class="sxs-lookup"><span data-stu-id="a5566-107">Default document.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-108">Fügt ein Standarddokument hinzu.</span><span class="sxs-lookup"><span data-stu-id="a5566-108">Adds a default document.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-109">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-109">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDefaultDocuments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithDefaultDocuments (System.Collections.Generic.IList&lt;string&gt; documents);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithDefaultDocuments(class System.Collections.Generic.IList`1&lt;string&gt; documents) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithDefaultDocuments(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultDocuments (documents As IList(Of String)) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultDocuments : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithDefaultDocuments documents" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="documents" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="documents"><span data-ttu-id="a5566-110">Liste der Standarddokumente.</span><span class="sxs-lookup"><span data-stu-id="a5566-110">List of default documents.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-111">Eine Liste der Standarddokumente hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="a5566-111">Adds a list of default documents.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-112">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-112">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithJavaVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithWebContainer&lt;FluentT&gt; WithJavaVersion (Microsoft.Azure.Management.AppService.Fluent.JavaVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithWebContainer`1&lt;!FluentT&gt; WithJavaVersion(class Microsoft.Azure.Management.AppService.Fluent.JavaVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithJavaVersion(Microsoft.Azure.Management.AppService.Fluent.JavaVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithJavaVersion (version As JavaVersion) As IWithWebContainer(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithJavaVersion : Microsoft.Azure.Management.AppService.Fluent.JavaVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithWebContainer&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithJavaVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithWebContainer&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.JavaVersion" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="a5566-113">Die Java-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-113">The Java version.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-114">Gibt die Java-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-114">Specifies the Java version.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-115">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-115">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithManagedPipelineMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithManagedPipelineMode (Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode managedPipelineMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithManagedPipelineMode(valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode managedPipelineMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithManagedPipelineMode(Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode)" />
      <MemberSignature Language="F#" Value="abstract member WithManagedPipelineMode : Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithManagedPipelineMode managedPipelineMode" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="managedPipelineMode" Type="Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode" />
      </Parameters>
      <Docs>
        <param name="managedPipelineMode"><span data-ttu-id="a5566-116">Verwalteter Pipelinemodus.</span><span class="sxs-lookup"><span data-stu-id="a5566-116">Managed pipeline mode.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-117">Gibt an, der verwaltete Pipelinemodus.</span><span class="sxs-lookup"><span data-stu-id="a5566-117">Specifies the managed pipeline mode.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-118">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-118">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNetFrameworkVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithNetFrameworkVersion (Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithNetFrameworkVersion(class Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithNetFrameworkVersion(Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNetFrameworkVersion (version As NetFrameworkVersion) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNetFrameworkVersion : Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithNetFrameworkVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="a5566-119">.NET Framework-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-119">The .NET Framework version.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-120">Gibt die .NET Framework-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-120">Specifies the .NET Framework version.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-121">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-121">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutDefaultDocument">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutDefaultDocument (string document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutDefaultDocument(string document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithoutDefaultDocument(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutDefaultDocument (document As String) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutDefaultDocument : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithoutDefaultDocument document" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="document"><span data-ttu-id="a5566-122">Standard-Dokument zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="a5566-122">Default document to remove.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-123">Entfernt ein Standarddokument an.</span><span class="sxs-lookup"><span data-stu-id="a5566-123">Removes a default document.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-124">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-124">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutJava">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutJava ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutJava() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithoutJava" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutJava () As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutJava : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithoutJava " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5566-125">Deaktivieren Sie Java-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="a5566-125">Turn off Java support.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-126">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-126">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPython">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithoutPython ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithoutPython() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithoutPython" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPython () As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithoutPython : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithoutPython " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5566-127">Deaktivieren Sie Python-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="a5566-127">Turn off Python support.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-128">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-128">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPhpVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithPhpVersion (Microsoft.Azure.Management.AppService.Fluent.PhpVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithPhpVersion(class Microsoft.Azure.Management.AppService.Fluent.PhpVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithPhpVersion(Microsoft.Azure.Management.AppService.Fluent.PhpVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPhpVersion (version As PhpVersion) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPhpVersion : Microsoft.Azure.Management.AppService.Fluent.PhpVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithPhpVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.PhpVersion" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="a5566-129">Die PHP-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-129">The PHP version.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-130">Gibt die PHP-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-130">Specifies the PHP version.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-131">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-131">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPlatformArchitecture">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithPlatformArchitecture (Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture platform);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithPlatformArchitecture(valuetype Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture platform) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithPlatformArchitecture(Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPlatformArchitecture (platform As PlatformArchitecture) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPlatformArchitecture : Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithPlatformArchitecture platform" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="platform" Type="Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture" />
      </Parameters>
      <Docs>
        <param name="platform"><span data-ttu-id="a5566-132">Die Plattformarchitektur.</span><span class="sxs-lookup"><span data-stu-id="a5566-132">The platform architecture.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-133">Gibt die Plattformarchitektur verwenden.</span><span class="sxs-lookup"><span data-stu-id="a5566-133">Specifies the platform architecture to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-134">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-134">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPythonVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithPythonVersion (Microsoft.Azure.Management.AppService.Fluent.PythonVersion version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithPythonVersion(class Microsoft.Azure.Management.AppService.Fluent.PythonVersion version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithPythonVersion(Microsoft.Azure.Management.AppService.Fluent.PythonVersion)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPythonVersion (version As PythonVersion) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPythonVersion : Microsoft.Azure.Management.AppService.Fluent.PythonVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithPythonVersion version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="Microsoft.Azure.Management.AppService.Fluent.PythonVersion" />
      </Parameters>
      <Docs>
        <param name="version"><span data-ttu-id="a5566-135">Die Python-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-135">The Python version.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-136">Gibt die Python-Version.</span><span class="sxs-lookup"><span data-stu-id="a5566-136">Specifies the Python version.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-137">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-137">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRemoteDebuggingDisabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithRemoteDebuggingDisabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithRemoteDebuggingDisabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithRemoteDebuggingDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRemoteDebuggingDisabled () As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRemoteDebuggingDisabled : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithRemoteDebuggingDisabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a5566-138">Deaktiviert das Remotedebuggen.</span><span class="sxs-lookup"><span data-stu-id="a5566-138">Disables remote debugging.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-139">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-139">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRemoteDebuggingEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithRemoteDebuggingEnabled (Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion remoteVisualStudioVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithRemoteDebuggingEnabled(class Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion remoteVisualStudioVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithRemoteDebuggingEnabled(Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion)" />
      <MemberSignature Language="F#" Value="abstract member WithRemoteDebuggingEnabled : Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithRemoteDebuggingEnabled remoteVisualStudioVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="remoteVisualStudioVersion" Type="Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion" />
      </Parameters>
      <Docs>
        <param name="remoteVisualStudioVersion"><span data-ttu-id="a5566-140">Die Visual Studio-Version für das Remotedebuggen.</span><span class="sxs-lookup"><span data-stu-id="a5566-140">The Visual Studio version for remote debugging.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-141">Gibt die Visual Studio-Version für das Remotedebuggen.</span><span class="sxs-lookup"><span data-stu-id="a5566-141">Specifies the Visual Studio version for remote debugging.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-142">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-142">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWebAppAlwaysOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithWebAppAlwaysOn (bool alwaysOn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithWebAppAlwaysOn(bool alwaysOn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithWebAppAlwaysOn(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWebAppAlwaysOn (alwaysOn As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithWebAppAlwaysOn : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithWebAppAlwaysOn alwaysOn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="alwaysOn" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="alwaysOn"><span data-ttu-id="a5566-143">"True", wenn die Web-app immer eingeschaltet ist.</span><span class="sxs-lookup"><span data-stu-id="a5566-143">True if the web app is always powered on.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-144">Gibt an, ob der virtuelle Computer einschalten der Web-app immer eingeschaltet ist.</span><span class="sxs-lookup"><span data-stu-id="a5566-144">Specifies if the VM powering the web app is always powered on.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-145">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-145">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWebSocketsEnabled">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt; WithWebSocketsEnabled (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate`1&lt;!FluentT&gt; WithWebSocketsEnabled(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IWithSiteConfigs`1.WithWebSocketsEnabled(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWebSocketsEnabled (enabled As Boolean) As IUpdate(Of FluentT)" />
      <MemberSignature Language="F#" Value="abstract member WithWebSocketsEnabled : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;'FluentT&gt;" Usage="iWithSiteConfigs.WithWebSocketsEnabled enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppBase.Update.IUpdate&lt;FluentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="a5566-146">"True", wenn WebSockets aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="a5566-146">True if web sockets are enabled.</span></span></param>
        <summary>
            <span data-ttu-id="a5566-147">Gibt an, ob WebSockets aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="a5566-147">Specifies if web sockets are enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a5566-148">Die nächste Phase der Aktualisierung der Web-app.</span><span class="sxs-lookup"><span data-stu-id="a5566-148">The next stage of web app update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>