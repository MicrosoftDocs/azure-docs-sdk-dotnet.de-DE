<Type Name="JobPreparation" FullName="Microsoft.Azure.Management.BatchAI.Models.JobPreparation">
  <TypeSignature Language="C#" Value="public class JobPreparation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobPreparation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparation" />
  <TypeSignature Language="F#" Value="type JobPreparation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9214e-101">Gibt die Einstellungen für die Vorbereitung des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="9214e-101">Specifies the settings for job preparation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobPreparation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9214e-102">Initialisiert eine neue Instanz der JobPreparation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9214e-102">Initializes a new instance of the JobPreparation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparation (string commandLine);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobPreparation.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (commandLine As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobPreparation : string -&gt; Microsoft.Azure.Management.BatchAI.Models.JobPreparation" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobPreparation commandLine" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="9214e-103">Die auszuführende Befehlszeile an.</span><span class="sxs-lookup"><span data-stu-id="9214e-103">The command line to execute.</span></span></param>
        <summary>
            <span data-ttu-id="9214e-104">Initialisiert eine neue Instanz der JobPreparation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9214e-104">Initializes a new instance of the JobPreparation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobPreparation.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobPreparation.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9214e-105">Ruft ab oder legt die auszuführende Befehlszeile an.</span><span class="sxs-lookup"><span data-stu-id="9214e-105">Gets or sets the command line to execute.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9214e-106">Wenn ContainerSettings für den Auftrag angegeben ist, wird diese CommandLine im gleichen Container als Auftrag ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="9214e-106">If containerSettings is specified on the job, this commandLine will be executed in the same container as job.</span></span> <span data-ttu-id="9214e-107">Andernfalls wird er auf den Knoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="9214e-107">Otherwise it will be executed on the node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobPreparation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparation.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9214e-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9214e-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9214e-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9214e-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>