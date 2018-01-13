<Type Name="AzureReachabilityReportParameters" FullName="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters">
  <TypeSignature Language="C#" Value="public class AzureReachabilityReportParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureReachabilityReportParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureReachabilityReportParameters" />
  <TypeSignature Language="F#" Value="type AzureReachabilityReportParameters = class" />
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
            Geografische und Zeit-Einschränkungen für Azure Erreichbarkeit Bericht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureReachabilityReportParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureReachabilityReportParameters (Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation providerLocation, DateTime startTime, DateTime endTime, System.Collections.Generic.IList&lt;string&gt; providers = null, System.Collections.Generic.IList&lt;string&gt; azureLocations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation providerLocation, valuetype System.DateTime startTime, valuetype System.DateTime endTime, class System.Collections.Generic.IList`1&lt;string&gt; providers, class System.Collections.Generic.IList`1&lt;string&gt; azureLocations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.#ctor(Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation,System.DateTime,System.DateTime,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (providerLocation As AzureReachabilityReportLocation, startTime As DateTime, endTime As DateTime, Optional providers As IList(Of String) = null, Optional azureLocations As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters : Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation * DateTime * DateTime * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters" Usage="new Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters (providerLocation, startTime, endTime, providers, azureLocations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="providerLocation" Type="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="endTime" Type="System.DateTime" />
        <Parameter Name="providers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="azureLocations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="providerLocation">To be added.</param>
        <param name="startTime">Die Startzeit für den Azure Erreichbarkeit Bericht.</param>
        <param name="endTime">Die Endzeit für den Azure Erreichbarkeit Bericht.</param>
        <param name="providers">Liste der Internetdienstanbieter.</param>
        <param name="azureLocations">Optionale Azure-Regionen, die Abfrage zum Bereich festzulegen.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureReachabilityReportParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureLocations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AzureLocations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AzureLocations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.AzureLocations" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureLocations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AzureLocations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.AzureLocations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureLocations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest optionale Azure-Regionen, um die Abfrage zu konzentrieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public DateTime EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.EndTime : DateTime with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Endzeit für den Azure Erreichbarkeit Bericht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProviderLocation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation ProviderLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation ProviderLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.ProviderLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property ProviderLocation As AzureReachabilityReportLocation" />
      <MemberSignature Language="F#" Value="member this.ProviderLocation : Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.ProviderLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="providerLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AzureReachabilityReportLocation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Providers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Providers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Providers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.Providers" />
      <MemberSignature Language="VB.NET" Value="Public Property Providers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Providers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.Providers" />
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
            Ruft ab oder legt die Liste der Internetdienstanbieter.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit für den Azure Erreichbarkeit Bericht fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.AzureReachabilityReportParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="azureReachabilityReportParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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