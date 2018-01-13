<Type Name="AvailableProvidersListState" FullName="Microsoft.Azure.Management.Network.Models.AvailableProvidersListState">
  <TypeSignature Language="C#" Value="public class AvailableProvidersListState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AvailableProvidersListState extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AvailableProvidersListState" />
  <TypeSignature Language="VB.NET" Value="Public Class AvailableProvidersListState" />
  <TypeSignature Language="F#" Value="type AvailableProvidersListState = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0f3cd-101">Zustandsdetails.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-101">State details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersListState ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0f3cd-102">Initialisiert eine neue Instanz der AvailableProvidersListState-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-102">Initializes a new instance of the AvailableProvidersListState class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AvailableProvidersListState (string stateName = null, System.Collections.Generic.IList&lt;string&gt; providers = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt; cities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string stateName, class System.Collections.Generic.IList`1&lt;string&gt; providers, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt; cities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional stateName As String = null, Optional providers As IList(Of String) = null, Optional cities As IList(Of AvailableProvidersListCity) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AvailableProvidersListState : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt; -&gt; Microsoft.Azure.Management.Network.Models.AvailableProvidersListState" Usage="new Microsoft.Azure.Management.Network.Models.AvailableProvidersListState (stateName, providers, cities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stateName" Type="System.String" />
        <Parameter Name="providers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="cities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt;" />
      </Parameters>
      <Docs>
        <param name="stateName"><span data-ttu-id="0f3cd-103">Der Statusname.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-103">The state name.</span></span></param>
        <param name="providers"><span data-ttu-id="0f3cd-104">Eine Liste der Internetdienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-104">A list of Internet service providers.</span></span></param>
        <param name="cities"><span data-ttu-id="0f3cd-105">Liste der verfügbaren Städte oder Städte in den Zustand.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-105">List of available cities or towns in the state.</span></span></param>
        <summary>
            <span data-ttu-id="0f3cd-106">Initialisiert eine neue Instanz der AvailableProvidersListState-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-106">Initializes a new instance of the AvailableProvidersListState class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt; Cities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt; Cities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.Cities" />
      <MemberSignature Language="VB.NET" Value="Public Property Cities As IList(Of AvailableProvidersListCity)" />
      <MemberSignature Language="F#" Value="member this.Cities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.Cities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.AvailableProvidersListCity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3cd-107">Ruft ab oder legt die Liste der verfügbaren Städte oder Städte in den Zustand fest.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-107">Gets or sets list of available cities or towns in the state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Providers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Providers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Providers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.Providers" />
      <MemberSignature Language="VB.NET" Value="Public Property Providers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Providers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.Providers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3cd-108">Ruft ab oder legt eine Liste der Internetdienstanbieter.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-108">Gets or sets a list of Internet service providers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateName">
      <MemberSignature Language="C#" Value="public string StateName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StateName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.StateName" />
      <MemberSignature Language="VB.NET" Value="Public Property StateName As String" />
      <MemberSignature Language="F#" Value="member this.StateName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.AvailableProvidersListState.StateName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f3cd-109">Ruft ab oder legt den Namen des Zustands.</span><span class="sxs-lookup"><span data-stu-id="0f3cd-109">Gets or sets the state name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>