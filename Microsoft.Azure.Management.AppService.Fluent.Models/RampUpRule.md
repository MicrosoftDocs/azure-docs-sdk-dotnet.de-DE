<Type Name="RampUpRule" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule">
  <TypeSignature Language="C#" Value="public class RampUpRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RampUpRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule" />
  <TypeSignature Language="VB.NET" Value="Public Class RampUpRule" />
  <TypeSignature Language="F#" Value="type RampUpRule = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Verteilerregeln für Ramp-up testen. Mit dieser Regel können statische Datenverkehr % in einem Einschubfach umleiten oder allmählich routing % basierend auf der Leistung zu ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RampUpRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RampUpRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RampUpRule (string actionHostName = null, Nullable&lt;double&gt; reroutePercentage = null, Nullable&lt;double&gt; changeStep = null, Nullable&lt;int&gt; changeIntervalInMinutes = null, Nullable&lt;double&gt; minReroutePercentage = null, Nullable&lt;double&gt; maxReroutePercentage = null, string changeDecisionCallbackUrl = null, string name = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string actionHostName, valuetype System.Nullable`1&lt;float64&gt; reroutePercentage, valuetype System.Nullable`1&lt;float64&gt; changeStep, valuetype System.Nullable`1&lt;int32&gt; changeIntervalInMinutes, valuetype System.Nullable`1&lt;float64&gt; minReroutePercentage, valuetype System.Nullable`1&lt;float64&gt; maxReroutePercentage, string changeDecisionCallbackUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.#ctor(System.String,System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional actionHostName As String = null, Optional reroutePercentage As Nullable(Of Double) = null, Optional changeStep As Nullable(Of Double) = null, Optional changeIntervalInMinutes As Nullable(Of Integer) = null, Optional minReroutePercentage As Nullable(Of Double) = null, Optional maxReroutePercentage As Nullable(Of Double) = null, Optional changeDecisionCallbackUrl As String = null, Optional name As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule : string * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule (actionHostName, reroutePercentage, changeStep, changeIntervalInMinutes, minReroutePercentage, maxReroutePercentage, changeDecisionCallbackUrl, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="actionHostName" Type="System.String" />
        <Parameter Name="reroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeStep" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeIntervalInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minReroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maxReroutePercentage" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="changeDecisionCallbackUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="actionHostName">Hostname des einen Slot, der Datenverkehr umgeleitet wird, wenn entschieden. Beispiel:
            "MyApp"-stage.azurewebsites.net.</param>
        <param name="reroutePercentage">Prozentsatz des Datenverkehrs dem umgeleitet wird, &lt;Code&gt;ActionHostName&lt;/code&gt;.</param>
        <param name="changeStep">In Automatisches Ramp-up Szenario ist dies der Schritt zum Hinzufügen/Entfernen von &lt;Code&gt;ReroutePercentage&lt;/code&gt; bis erreicht &lt;Code&gt;MinReroutePercentage &lt; /code &gt; oder &lt;Code&gt;MaxReroutePercentage&lt;/code&gt;. Standortmetriken werden überprüft alle N Minuten angegebene in &lt;Code&gt;ChangeIntervalInMinutes&lt;/code&gt;.
            Benutzerdefinierte Decision-Algorithmus kann bereitgestellt werden, in TiPCallback-Website-Erweiterung, die URL angegeben werden kann &lt;Code&gt;ChangeDecisionCallbackUrl&lt;/code&gt;.</param>
        <param name="changeIntervalInMinutes">Gibt Intervall in Mimuntes ReroutePercentage auswertet.</param>
        <param name="minReroutePercentage">Gibt die untere Grenze höher die ReroutePercentage verbleibt.</param>
        <param name="maxReroutePercentage">Gibt an, obere Grenze unten die ReroutePercentage verbleibt.</param>
        <param name="changeDecisionCallbackUrl">Benutzerdefinierte Decision-Algorithmus kann in TiPCallback websiteerweiterung bereitgestellt werden, der URL angegeben werden kann. Finden Sie unter TiPCallback websiteerweiterung für das Gerüst und Verträge.
            https://www.siteextensions.NET/Packages/TiPCallback/</param>
        <param name="name">Name der Regel für das routing. Der empfohlene Name wäre, in das Einschubfach verweisen, die der Datenverkehr im Experiment empfangen wird.</param>
        <summary>
            Initialisiert eine neue Instanz der RampUpRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActionHostName">
      <MemberSignature Language="C#" Value="public string ActionHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActionHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ActionHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property ActionHostName As String" />
      <MemberSignature Language="F#" Value="member this.ActionHostName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ActionHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="actionHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Hostnamen des einen Slot, der Datenverkehr umgeleitet wird, wenn beschlossen. Beispiel: "MyApp"-stage.azurewebsites.net.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeDecisionCallbackUrl">
      <MemberSignature Language="C#" Value="public string ChangeDecisionCallbackUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ChangeDecisionCallbackUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ChangeDecisionCallbackUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeDecisionCallbackUrl As String" />
      <MemberSignature Language="F#" Value="member this.ChangeDecisionCallbackUrl : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ChangeDecisionCallbackUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeDecisionCallbackUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest benutzerdefinierten Decision-Algorithmus in TiPCallback bereitgestellt werden kann websiteerweiterung der URL angegeben werden kann. Finden Sie unter TiPCallback websiteerweiterung für das Gerüst und Verträge.
            https://www.siteextensions.NET/Packages/TiPCallback/
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeIntervalInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ChangeIntervalInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ChangeIntervalInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ChangeIntervalInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeIntervalInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ChangeIntervalInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ChangeIntervalInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeIntervalInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt Intervall in Mimuntes ReroutePercentage auswertet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChangeStep">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ChangeStep { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ChangeStep" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ChangeStep" />
      <MemberSignature Language="VB.NET" Value="Public Property ChangeStep As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ChangeStep : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ChangeStep" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="changeStep")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, in Automatisches Ramp-up Szenario dies der Schritt zum Hinzufügen ist/Entfernen von &amp;Lt; Code&amp;Gt; ReroutePercentage&amp;Lt; / code&amp;Gt; bis erreicht &amp;Lt; Code&amp;Gt; MinReroutePercentage&amp;Lt; / code&amp;Gt; oder &amp;Lt; Code&amp;Gt; MaxReroutePercentage&amp;Lt; / code&amp;Gt;. Standortmetriken werden überprüft alle N Minuten angegebene in &amp;Lt; Code&amp;Gt; ChangeIntervalInMinutes&amp;Lt; / code&amp;Gt;.
            Benutzerdefinierte Decision-Algorithmus kann bereitgestellt werden, in TiPCallback-Website-Erweiterung, die URL angegeben werden kann &amp;Lt; Code&amp;Gt; ChangeDecisionCallbackUrl&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MaxReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MaxReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.MaxReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MaxReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.MaxReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxReroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt Obergrenze unten die ReroutePercentage verbleibt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; MinReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; MinReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.MinReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property MinReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.MinReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.MinReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minReroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest gibt die untere Grenze höher die ReroutePercentage verbleibt an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Regel routing fest. Der empfohlene Name wäre, in das Einschubfach verweisen, die der Datenverkehr im Experiment empfangen wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReroutePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; ReroutePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; ReroutePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ReroutePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property ReroutePercentage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.ReroutePercentage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.RampUpRule.ReroutePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reroutePercentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Prozentsatz des Datenverkehrs dem umgeleitet wird, &amp;Lt; Code&amp;Gt; ActionHostName&amp;Lt; / code&amp;Gt;.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>