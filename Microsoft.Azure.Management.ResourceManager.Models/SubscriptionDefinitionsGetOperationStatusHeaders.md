<Type Name="SubscriptionDefinitionsGetOperationStatusHeaders" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders">
  <TypeSignature Language="C#" Value="public class SubscriptionDefinitionsGetOperationStatusHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionDefinitionsGetOperationStatusHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionDefinitionsGetOperationStatusHeaders" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsGetOperationStatusHeaders = class" />
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
            Definiert die Header für GetOperationStatus-Vorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsGetOperationStatusHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SubscriptionDefinitionsGetOperationStatusHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsGetOperationStatusHeaders (string location = null, string retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders (location, retryAfter)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="retryAfter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">Die URL, in denen der Status des asynchronen Vorgangs überprüft werden kann.</param>
        <param name="retryAfter">Die Menge der Verzögerung verwenden, während der Status des Vorgangs überprüft wird. Der Wert wird in Sekunden angegeben.</param>
        <summary>
            Initialisiert eine neue Instanz der SubscriptionDefinitionsGetOperationStatusHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL fest, in denen der Status des asynchronen Vorgangs überprüft werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public string RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As String" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsGetOperationStatusHeaders.RetryAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Retry-After")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Dauer der Verzögerung verwenden, während der Status des Vorgangs überprüft wird. Der Wert wird in Sekunden angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>