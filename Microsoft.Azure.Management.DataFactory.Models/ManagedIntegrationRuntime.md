<Type Name="ManagedIntegrationRuntime" FullName="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime">
  <TypeSignature Language="C#" Value="public class ManagedIntegrationRuntime : Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntime" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ManagedIntegrationRuntime extends Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntime" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime" />
  <TypeSignature Language="VB.NET" Value="Public Class ManagedIntegrationRuntime&#xA;Inherits IntegrationRuntime" />
  <TypeSignature Language="F#" Value="type ManagedIntegrationRuntime = class&#xA;    inherit IntegrationRuntime" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntime</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Managed")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Verwaltete integrationslaufzeit, einschließlich verwalteter elastischen und verwalteten dedizierten Integration Laufzeiten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntime ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ManagedIntegrationRuntime-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ManagedIntegrationRuntime (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string state = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties computeProperties = null, Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties ssisProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string state, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties computeProperties, class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties ssisProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties,Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional description As String = null, Optional state As String = null, Optional computeProperties As IntegrationRuntimeComputeProperties = null, Optional ssisProperties As IntegrationRuntimeSsisProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties * Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties -&gt; Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime" Usage="new Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime (additionalProperties, description, state, computeProperties, ssisProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="computeProperties" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties" />
        <Parameter Name="ssisProperties" Type="Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung der Integration-Laufzeit.</param>
        <param name="state">Integration-Laufzeitstatus, nur für verwaltete dedizierten integrationslaufzeit gültig. Folgende Werte sind möglich: "Ursprünglichen", "Angehalten", "Gestartet", "starten", "Beenden", "needregistration" "", "Online", "Beschränkt", "Offline"</param>
        <param name="computeProperties">Die Serverressource für verwaltete integrationslaufzeit.</param>
        <param name="ssisProperties">SSIS-Eigenschaften für verwaltete integrationslaufzeit.</param>
        <summary>
            Initialisiert eine neue Instanz der ManagedIntegrationRuntime-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputeProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties ComputeProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties ComputeProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.ComputeProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputeProperties As IntegrationRuntimeComputeProperties" />
      <MemberSignature Language="F#" Value="member this.ComputeProperties : Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.ComputeProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.computeProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeComputeProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Serverressource für verwaltete integrationslaufzeit.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SsisProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties SsisProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties SsisProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.SsisProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property SsisProperties As IntegrationRuntimeSsisProperties" />
      <MemberSignature Language="F#" Value="member this.SsisProperties : Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.SsisProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.ssisProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeSsisProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie SSIS-Eigenschaften für die Laufzeit verwaltete Integration fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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
            Ruft die Integration Laufzeitzustand, nur gültig für verwaltete dedizierten integrationslaufzeit ab. Folgende Werte sind möglich: "Ursprünglichen", "Angehalten", "Gestartet", "starten", "Beenden", "needregistration" "", "Online", "Beschränkt", "Offline"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ManagedIntegrationRuntime.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="managedIntegrationRuntime.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
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