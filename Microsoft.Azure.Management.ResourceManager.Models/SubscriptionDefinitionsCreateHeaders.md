<Type Name="SubscriptionDefinitionsCreateHeaders" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders">
  <TypeSignature Language="C#" Value="public class SubscriptionDefinitionsCreateHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionDefinitionsCreateHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionDefinitionsCreateHeaders" />
  <TypeSignature Language="F#" Value="type SubscriptionDefinitionsCreateHeaders = class" />
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
            Definiert die Header für den Erstellungsvorgang.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsCreateHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SubscriptionDefinitionsCreateHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionDefinitionsCreateHeaders (string location = null, string retryAfter = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string retryAfter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional location As String = null, Optional retryAfter As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders : string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders (location, retryAfter)" />
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
        <param name="location">ABGERUFEN Sie diese URL beim Abrufen des Status des asynchronen Vorgangs werden.</param>
        <param name="retryAfter">Die Menge der Verzögerung verwenden, während der Status des Vorgangs überprüft wird. Der Wert wird in Sekunden angegeben.</param>
        <summary>
            Initialisiert eine neue Instanz der SubscriptionDefinitionsCreateHeaders-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.Location" />
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
            Ruft ab oder legt diese URL beim Abrufen des Status des asynchronen Vorgangs ABGERUFEN werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryAfter">
      <MemberSignature Language="C#" Value="public string RetryAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RetryAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.RetryAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryAfter As String" />
      <MemberSignature Language="F#" Value="member this.RetryAfter : string with get, set" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionDefinitionsCreateHeaders.RetryAfter" />
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