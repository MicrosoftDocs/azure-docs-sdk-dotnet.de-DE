<Type Name="UpdateIntegrationRuntimeNodeRequest" FullName="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest">
  <TypeSignature Language="C#" Value="public class UpdateIntegrationRuntimeNodeRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UpdateIntegrationRuntimeNodeRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class UpdateIntegrationRuntimeNodeRequest" />
  <TypeSignature Language="F#" Value="type UpdateIntegrationRuntimeNodeRequest = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Anforderung zum Update Integration Runtime Knoten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateIntegrationRuntimeNodeRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der UpdateIntegrationRuntimeNodeRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UpdateIntegrationRuntimeNodeRequest (Nullable&lt;int&gt; concurrentJobsLimit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; concurrentJobsLimit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest.#ctor(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional concurrentJobsLimit As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest : Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest" Usage="new Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest concurrentJobsLimit" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="concurrentJobsLimit" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="concurrentJobsLimit">Die Anzahl von gleichzeitigen Aufträgen, die auf dem Integration Common Language Runtime-Knoten ausgeführt werden darf. Werte zwischen 1 und maxConcurrentJobs(inclusive) sind zulässig.</param>
        <summary>
            Initialisiert eine neue Instanz der UpdateIntegrationRuntimeNodeRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConcurrentJobsLimit">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ConcurrentJobsLimit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ConcurrentJobsLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest.ConcurrentJobsLimit" />
      <MemberSignature Language="VB.NET" Value="Public Property ConcurrentJobsLimit As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ConcurrentJobsLimit : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest.ConcurrentJobsLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="concurrentJobsLimit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von gleichzeitigen Aufträgen, die auf dem Integration Common Language Runtime-Knoten ausgeführt werden darf. Werte zwischen 1 und maxConcurrentJobs(inclusive) sind zulässig.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.UpdateIntegrationRuntimeNodeRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="updateIntegrationRuntimeNodeRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
  </Members>
</Type>