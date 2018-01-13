<Type Name="RegenerateAccessKeyParameters" FullName="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters">
  <TypeSignature Language="C#" Value="public class RegenerateAccessKeyParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RegenerateAccessKeyParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class RegenerateAccessKeyParameters" />
  <TypeSignature Language="F#" Value="type RegenerateAccessKeyParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Parameter für den Vorgang erneut generieren Autorisierungsregel bereitgestellte gibt an, welche Schlüssel Neeeds zurückgesetzt werden sollen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateAccessKeyParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RegenerateAccessKeyParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RegenerateAccessKeyParameters (Microsoft.Azure.Management.EventHub.Models.KeyType keyType, string key = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.EventHub.Models.KeyType keyType, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.#ctor(Microsoft.Azure.Management.EventHub.Models.KeyType,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters : Microsoft.Azure.Management.EventHub.Models.KeyType * string -&gt; Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters" Usage="new Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters (keyType, key)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyType" Type="Microsoft.Azure.Management.EventHub.Models.KeyType" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyType">Der Zugriffsschlüssel erneut generieren. Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"</param>
        <param name="key">Optional, wenn der Schlüsselwert angegeben, wird festgelegt, für den "KeyType" oder der automatisch generierten Schlüssel-Wert für "KeyType" festgelegt</param>
        <summary>
            Initialisiert eine neue Instanz der RegenerateAccessKeyParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public string Key { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.Key" />
      <MemberSignature Language="VB.NET" Value="Public Property Key As String" />
      <MemberSignature Language="F#" Value="member this.Key : string with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="key")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest optional, wenn der Schlüsselwert angegeben, wird festgelegt, für den "KeyType" oder der automatisch generierten Schlüssel-Wert für "KeyType" festgelegt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.EventHub.Models.KeyType KeyType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.EventHub.Models.KeyType KeyType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.KeyType" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyType As KeyType" />
      <MemberSignature Language="F#" Value="member this.KeyType : Microsoft.Azure.Management.EventHub.Models.KeyType with get, set" Usage="Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.KeyType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventHub.Models.KeyType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zugriffsschlüssel erneut generieren. Folgende Werte sind möglich: "PrimaryKey", "SecondaryKey"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventHub.Models.RegenerateAccessKeyParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="regenerateAccessKeyParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventHub</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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