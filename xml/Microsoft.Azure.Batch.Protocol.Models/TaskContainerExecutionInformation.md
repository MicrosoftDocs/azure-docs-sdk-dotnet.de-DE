<Type Name="TaskContainerExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskContainerExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskContainerExecutionInformation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2ddc6-101">Enthält Informationen über den Container, die eine Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-101">Contains information about the container which a task is executing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ddc6-102">Initialisiert eine neue Instanz der TaskContainerExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-102">Initializes a new instance of the TaskContainerExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerExecutionInformation (string containerId = null, string state = null, string error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerId, string state, string error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional containerId As String = null, Optional state As String = null, Optional error As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation (containerId, state, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="error" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerId"><span data-ttu-id="2ddc6-103">Die ID des Containers.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-103">The ID of the container.</span></span></param>
        <param name="state"><span data-ttu-id="2ddc6-104">Der Zustand des Containers.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-104">The state of the container.</span></span></param>
        <param name="error"><span data-ttu-id="2ddc6-105">Ausführliche Fehlerinformationen über den Container.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-105">Detailed error information about the container.</span></span></param>
        <summary>
            <span data-ttu-id="2ddc6-106">Initialisiert eine neue Instanz der TaskContainerExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-106">Initializes a new instance of the TaskContainerExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.ContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ddc6-107">Ruft ab oder legt die ID des Containers fest.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-107">Gets or sets the ID of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public string Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As String" />
      <MemberSignature Language="F#" Value="member this.Error : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ddc6-108">Ruft ab, oder legt Sie ausführliche Fehlerinformationen über den Container fest.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-108">Gets or sets detailed error information about the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ddc6-109">Dies ist die detaillierte Fehlerzeichenfolge aus dem Docker-Dienst, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-109">This is the detailed error string from the Docker service, if available.</span></span> <span data-ttu-id="2ddc6-110">Dies ist äquivalent zum Fehlerfeld von "Docker überprüfen" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-110">It is equivalent to the error field returned by "docker inspect".</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ddc6-111">Ruft ab oder legt den Zustand des Containers fest.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-111">Gets or sets the state of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ddc6-112">Dies ist der Zustand des Containers entsprechend den Docker-Dienst.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-112">This is the state of the container according to the Docker service.</span></span>
            <span data-ttu-id="2ddc6-113">Dies ist äquivalent zum Statusfeld von "Docker überprüfen" zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="2ddc6-113">It is equivalent to the status field returned by "docker inspect".</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>