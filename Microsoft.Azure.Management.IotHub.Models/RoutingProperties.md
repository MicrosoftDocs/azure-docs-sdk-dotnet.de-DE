<Type Name="RoutingProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingProperties">
  <TypeSignature Language="C#" Value="public class RoutingProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingProperties" />
  <TypeSignature Language="F#" Value="type RoutingProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Das routing speicherbezogenen Eigenschaften der IoT Hub. Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RoutingProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingProperties (Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints endpoints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt; routes = null, Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties fallbackRoute = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints endpoints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt; routes, class Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties fallbackRoute) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingProperties.#ctor(Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints,System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RouteProperties},Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional endpoints As RoutingEndpoints = null, Optional routes As IList(Of RouteProperties) = null, Optional fallbackRoute As FallbackRouteProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingProperties : Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt; * Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingProperties (endpoints, routes, fallbackRoute)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endpoints" Type="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints" />
        <Parameter Name="routes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt;" />
        <Parameter Name="fallbackRoute" Type="Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties" />
      </Parameters>
      <Docs>
        <param name="endpoints">To be added.</param>
        <param name="routes">Die Liste der vom Benutzer bereitgestellte Routingregeln, die zum Weiterleiten von Nachrichten an integrierte und benutzerdefinierte Endpunkte IoT Hub verwendet. Dürfen maximal 100 Verteilerregeln für kostenpflichtige Hubs und maximal 5 Routingregeln sind kostenlos Hubs zulässig.</param>
        <param name="fallbackRoute">Die Eigenschaften der Route, die verwendet wird, als eine Route fallen zurück, wenn keine der im Abschnitt "leitet" angegebenen Bedingungen erfüllt sind. Dieser Parameter ist optional. Wenn diese Eigenschaft nicht festgelegt ist, Nachrichten, die nicht im Abschnitt "leitet" angegebenen Bedingungen erfüllen an den integrierten Eventhub-Endpunkt weitergeleitet.</param>
        <summary>
            Initialisiert eine neue Instanz der RoutingProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints Endpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingProperties.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoints As RoutingEndpoints" />
      <MemberSignature Language="F#" Value="member this.Endpoints : Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingProperties.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FallbackRoute">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties FallbackRoute { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties FallbackRoute" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingProperties.FallbackRoute" />
      <MemberSignature Language="VB.NET" Value="Public Property FallbackRoute As FallbackRouteProperties" />
      <MemberSignature Language="F#" Value="member this.FallbackRoute : Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingProperties.FallbackRoute" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fallbackRoute")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.FallbackRouteProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften der Route, die als eine Route fallen Back verwendet wird, wenn keine der im Abschnitt "leitet" angegebenen Bedingungen erfüllt sind. Dieser Parameter ist optional. Wenn diese Eigenschaft nicht festgelegt ist, Nachrichten, die nicht im Abschnitt "leitet" angegebenen Bedingungen erfüllen an den integrierten Eventhub-Endpunkt weitergeleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt; Routes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt; Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingProperties.Routes" />
      <MemberSignature Language="VB.NET" Value="Public Property Routes As IList(Of RouteProperties)" />
      <MemberSignature Language="F#" Value="member this.Routes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingProperties.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RouteProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der vom Benutzer bereitgestellte Routingregeln, die der IoT Hub verwendet zum Weiterleiten von Nachrichten an integrierte und benutzerdefinierte Endpunkte. Dürfen maximal 100 Verteilerregeln für kostenpflichtige Hubs und maximal 5 Routingregeln sind kostenlos Hubs zulässig.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routingProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
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