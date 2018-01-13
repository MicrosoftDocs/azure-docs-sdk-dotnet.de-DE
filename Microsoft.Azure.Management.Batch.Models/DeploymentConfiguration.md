<Type Name="DeploymentConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration">
  <TypeSignature Language="C#" Value="public class DeploymentConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentConfiguration" />
  <TypeSignature Language="F#" Value="type DeploymentConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bereitstellung von Konfigurationseigenschaften.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DeploymentConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentConfiguration (Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration cloudServiceConfiguration = null, Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration virtualMachineConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration cloudServiceConfiguration, class Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration virtualMachineConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.#ctor(Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration,Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration : Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration * Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration -&gt; Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration (cloudServiceConfiguration, virtualMachineConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="cloudServiceConfiguration" Type="Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration" />
      </Parameters>
      <Docs>
        <param name="cloudServiceConfiguration">Die Clouddienstkonfiguration des Pools.</param>
        <param name="virtualMachineConfiguration">Die VM-Konfiguration des Pools.</param>
        <summary>
            Initialisiert eine neue Instanz der DeploymentConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration CloudServiceConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration CloudServiceConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.CloudServiceConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceConfiguration As CloudServiceConfiguration" />
      <MemberSignature Language="F#" Value="member this.CloudServiceConfiguration : Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.CloudServiceConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudServiceConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Cloud-Dienstkonfiguration für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft und die VirtualMachineConfiguration schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden. Diese Eigenschaft nicht angegeben wird, wenn das Batch-Konto, wobei seine PoolAllocationMode-Eigenschaft auf "UserSubscription" festgelegt erstellt wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Konfiguration der virtuellen Maschine für den Pool.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft und die CloudServiceConfiguration schließen sich gegenseitig aus, und eine der Eigenschaften muss angegeben werden.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>