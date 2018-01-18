<Type Name="IServiceConfigurationOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations">
  <TypeSignature Language="C#" Value="public interface IServiceConfigurationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IServiceConfigurationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IServiceConfigurationOperations" />
  <TypeSignature Language="F#" Value="type IServiceConfigurationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="996bd-101">Alle Vorgänge im Zusammenhang mit Dienstkonfigurationen</span><span class="sxs-lookup"><span data-stu-id="996bd-101">All Operations related to Service configurations</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.BeginCreatingAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreatingAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iServiceConfigurationOperations.BeginCreatingAsync (serviceConfiguration, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceConfiguration">
            <span data-ttu-id="996bd-102">Parameter für das Erstellen von Speicherkonto beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="996bd-102">Parameters supplied to the Begin Creating Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="996bd-103">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="996bd-103">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="996bd-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="996bd-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="996bd-105">Der beginnen Erstellen von Speicherkonto-Vorgang erstellt ein neues Speicherkonto in Azure.</span><span class="sxs-lookup"><span data-stu-id="996bd-105">The Begin Creating Storage Account operation creates a new storage account in Azure.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="996bd-106">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="996bd-106">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration serviceConfiguration, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iServiceConfigurationOperations.CreateAsync (serviceConfiguration, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceConfiguration" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfiguration" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceConfiguration">
            <span data-ttu-id="996bd-107">Parameter für das Speicherkonto erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="996bd-107">Parameters supplied to the Create Storage Account operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="996bd-108">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="996bd-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="996bd-109">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="996bd-109">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="996bd-110">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="996bd-110">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customeRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;" Usage="iServiceConfigurationOperations.GetAsync (customeRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.ServiceConfigurationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customeRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customeRequestHeaders">To be added.</param>
        <param name="cancellationToken">
            <span data-ttu-id="996bd-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="996bd-111">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="996bd-112">Informationen über die Konfiguration des Diensts für die Ressource</span><span class="sxs-lookup"><span data-stu-id="996bd-112">Info about the service configuration regarding the resource</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>