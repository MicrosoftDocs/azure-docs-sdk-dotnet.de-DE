<Type Name="JobListParameters" FullName="Microsoft.Azure.Management.Automation.Models.JobListParameters">
  <TypeSignature Language="C#" Value="public class JobListParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobListParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.Models.JobListParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class JobListParameters" />
  <TypeSignature Language="F#" Value="type JobListParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c541b-101">Die Parameter für den Auftragsvorgang Liste angegeben.</span><span class="sxs-lookup"><span data-stu-id="c541b-101">The parameters supplied to the list job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobListParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.Models.JobListParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c541b-102">Initialisiert eine neue Instanz der JobListParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c541b-102">Initializes a new instance of the JobListParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public string EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobListParameters.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As String" />
      <MemberSignature Language="F#" Value="member this.EndTime : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobListParameters.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c541b-103">Optional.</span><span class="sxs-lookup"><span data-stu-id="c541b-103">Optional.</span></span> <span data-ttu-id="c541b-104">Für das Ende sollte Zeitfilter der Wert eine Datetime-Zeichenfolge im UTC-Format gemäß ISO 8601 sein.</span><span class="sxs-lookup"><span data-stu-id="c541b-104">For the end time filter the value should be a datetime string in UTC format as defined in ISO 8601.</span></span> <span data-ttu-id="c541b-105">Zum Beispiel: 2014-09-25T17:49:17.2252204Z</span><span class="sxs-lookup"><span data-stu-id="c541b-105">For example, 2014-09-25T17:49:17.2252204Z</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookName">
      <MemberSignature Language="C#" Value="public string RunbookName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunbookName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobListParameters.RunbookName" />
      <MemberSignature Language="VB.NET" Value="Public Property RunbookName As String" />
      <MemberSignature Language="F#" Value="member this.RunbookName : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobListParameters.RunbookName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c541b-106">Optional.</span><span class="sxs-lookup"><span data-stu-id="c541b-106">Optional.</span></span> <span data-ttu-id="c541b-107">Ruft ab oder legt die Runbook-Name des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="c541b-107">Gets or sets the runbook name of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public string StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobListParameters.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As String" />
      <MemberSignature Language="F#" Value="member this.StartTime : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobListParameters.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c541b-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="c541b-108">Optional.</span></span> <span data-ttu-id="c541b-109">Für den Beginn sollten Zeitfilter der Wert eine Datetime-Zeichenfolge im UTC-Format gemäß ISO 8601 sein.</span><span class="sxs-lookup"><span data-stu-id="c541b-109">For the start time filter the value should be a datetime string in UTC format as defined in ISO 8601.</span></span> <span data-ttu-id="c541b-110">Zum Beispiel: 2014-09-25T17:49:17.2252204Z</span><span class="sxs-lookup"><span data-stu-id="c541b-110">For example, 2014-09-25T17:49:17.2252204Z</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.Models.JobListParameters.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.Automation.Models.JobListParameters.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c541b-111">Optional.</span><span class="sxs-lookup"><span data-stu-id="c541b-111">Optional.</span></span> <span data-ttu-id="c541b-112">Ruft ab oder legt den Status des Auftrags fest.</span><span class="sxs-lookup"><span data-stu-id="c541b-112">Gets or sets the status of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>