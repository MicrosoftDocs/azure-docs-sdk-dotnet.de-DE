<Type Name="DeploymentValidateResult" FullName="Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult">
  <TypeSignature Language="C#" Value="public class DeploymentValidateResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeploymentValidateResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult" />
  <TypeSignature Language="VB.NET" Value="Public Class DeploymentValidateResult" />
  <TypeSignature Language="F#" Value="type DeploymentValidateResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Informationen über vorlagenbereitstellungsüberprüfung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentValidateResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DeploymentValidateResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeploymentValidateResult (Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails error = null, Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails error, class Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.#ctor(Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails,Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional error As ResourceManagementErrorWithDetails = null, Optional properties As DeploymentPropertiesExtended = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult : Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails * Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended -&gt; Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult" Usage="new Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult (error, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="error" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended" />
      </Parameters>
      <Docs>
        <param name="error">Validierungsfehler.</param>
        <param name="properties">Eigenschaften der Vorlage.</param>
        <summary>
            Initialisiert eine neue Instanz der DeploymentValidateResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As ResourceManagementErrorWithDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ResourceManagementErrorWithDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Validierungsfehler.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As DeploymentPropertiesExtended" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.DeploymentPropertiesExtended</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Vorlage Bereitstellungseigenschaften.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.DeploymentValidateResult.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="deploymentValidateResult.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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