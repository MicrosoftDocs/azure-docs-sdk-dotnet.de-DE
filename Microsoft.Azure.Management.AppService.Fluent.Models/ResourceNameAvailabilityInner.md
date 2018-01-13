<Type Name="ResourceNameAvailabilityInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner">
  <TypeSignature Language="C#" Value="public class ResourceNameAvailabilityInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceNameAvailabilityInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceNameAvailabilityInner" />
  <TypeSignature Language="F#" Value="type ResourceNameAvailabilityInner = class" />
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
            Informationen über erneut aus der Name einer Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNameAvailabilityInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ResourceNameAvailabilityInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceNameAvailabilityInner (Nullable&lt;bool&gt; nameAvailable = null, string reason = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; nameAvailable, string reason, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.#ctor(System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nameAvailable As Nullable(Of Boolean) = null, Optional reason As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner : Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner (nameAvailable, reason, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nameAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="reason" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameAvailable">&lt;Code&gt;"true"&lt;/code&gt; gibt an, dass Namen gültig und verfügbar. &lt;Code&gt;"false"&lt;/code&gt; gibt an, der Name ist ungültig, nicht verfügbar, oder beides.</param>
        <param name="reason">&lt;Code&gt;ungültige&lt;/code&gt; gibt an, der bereitgestellte Name stimmt nicht mit Azure App Service benennungsanforderungen überein.
            &lt;Code&gt;AlreadyExists&lt;/code&gt; gibt an, dass der Name bereits verwendet wird und daher nicht verfügbar ist. Folgende Werte sind möglich: "Ungültig", "AlreadyExists"</param>
        <param name="message">Wenn Grund == ungültig ist, geben Sie den Benutzer mit dem Grund, warum der angegebene Name ungültig ist, und geben Sie die Ressource benennungsanforderungen, sodass der Benutzer einen gültigen Namen auswählen kann. Wenn Grund == AlreadyExists, erklärt dieser Ressourcenname wird bereits verwendet, und Sie angewiesen, einen anderen Namen wählen.</param>
        <summary>
            Initialisiert eine neue Instanz der ResourceNameAvailabilityInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, wenn Grund == ungültig ist, geben Sie den Benutzer mit dem Grund, warum der angegebene Name ungültig ist, und geben Sie die Ressource benennungsanforderungen, sodass der Benutzer einen gültigen Namen auswählen kann. Wenn Grund == AlreadyExists, erklärt dieser Ressourcenname wird bereits verwendet, und Sie angewiesen, einen anderen Namen wählen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; NameAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; NameAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.NameAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property NameAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.NameAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.NameAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nameAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Gibt an, dass Namen gültig und verfügbar.
            &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; Gibt an, der Name ist ungültig, nicht verfügbar, oder beides.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reason">
      <MemberSignature Language="C#" Value="public string Reason { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Reason" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.Reason" />
      <MemberSignature Language="VB.NET" Value="Public Property Reason As String" />
      <MemberSignature Language="F#" Value="member this.Reason : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.ResourceNameAvailabilityInner.Reason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="reason")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; ungültige&amp;Lt; / code&amp;Gt; der angegebene Name entspricht nicht der Azure App Service benennungsanforderungen angibt.
            &amp;Lt; Code&amp;Gt; AlreadyExists&amp;Lt; / code&amp;Gt; Gibt an, dass der Name bereits verwendet wird und daher nicht verfügbar ist.
            Folgende Werte sind möglich: "Ungültig", "AlreadyExists"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>