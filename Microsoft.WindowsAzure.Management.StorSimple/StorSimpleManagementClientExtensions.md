<Type Name="StorSimpleManagementClientExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions">
  <TypeSignature Language="C#" Value="public static class StorSimpleManagementClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StorSimpleManagementClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StorSimpleManagementClientExtensions" />
  <TypeSignature Language="F#" Value="type StorSimpleManagementClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8cc10-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="8cc10-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetOperationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo GetOperationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo GetOperationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatus(Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatus (operations As IStorSimpleManagementClient, taskId As String) As TaskStatusInfo" />
      <MemberSignature Language="F#" Value="static member GetOperationStatus : Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient * string -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatus (operations, taskId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient" RefType="this" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8cc10-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.</span><span class="sxs-lookup"><span data-stu-id="8cc10-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="8cc10-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8cc10-103">Required.</span></span> <span data-ttu-id="8cc10-104">Der Task-Id für die Anforderung, die Sie nachverfolgen möchten.</span><span class="sxs-lookup"><span data-stu-id="8cc10-104">The task Id for the request you wish to track.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc10-105">Der Vorgangsstatus abrufen gibt den Status der angegebenen Task-Id zurück. Nach dem Aufrufen einer asynchronen Aufgabe an, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="8cc10-105">The Get Task Status returns the status of the specified task id. After calling an asynchronous task, you can call Get Task Status to determine whether the task has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc10-106">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="8cc10-106">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient operations, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOperationStatusAsync (operations As IStorSimpleManagementClient, taskId As String) As Task(Of TaskStatusInfo)" />
      <MemberSignature Language="F#" Value="static member GetOperationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.StorSimpleManagementClientExtensions.GetOperationStatusAsync (operations, taskId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient" RefType="this" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8cc10-107">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.</span><span class="sxs-lookup"><span data-stu-id="8cc10-107">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.</span></span>
            </param>
        <param name="taskId">
            <span data-ttu-id="8cc10-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8cc10-108">Required.</span></span> <span data-ttu-id="8cc10-109">Der Task-Id für die Anforderung, die Sie nachverfolgen möchten.</span><span class="sxs-lookup"><span data-stu-id="8cc10-109">The task Id for the request you wish to track.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc10-110">Der Vorgangsstatus abrufen gibt den Status der angegebenen Task-Id zurück. Nach dem Aufrufen einer asynchronen Aufgabe an, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="8cc10-110">The Get Task Status returns the status of the specified task id. After calling an asynchronous task, you can call Get Task Status to determine whether the task has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc10-111">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="8cc10-111">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>