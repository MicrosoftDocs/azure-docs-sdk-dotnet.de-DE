<Type Name="VerificationIPFlowResult" FullName="Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult">
  <TypeSignature Language="C#" Value="public class VerificationIPFlowResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VerificationIPFlowResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" />
  <TypeSignature Language="VB.NET" Value="Public Class VerificationIPFlowResult" />
  <TypeSignature Language="F#" Value="type VerificationIPFlowResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ergebnisse der Überprüfung der IP-Datenfluss für die Zielressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VerificationIPFlowResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VerificationIPFlowResult (string access = null, string ruleName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string access, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional access As String = null, Optional ruleName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult : string * string -&gt; Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult" Usage="new Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult (access, ruleName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="access">Gibt an, ob der Datenverkehr zugelassen oder verweigert wird. Folgende Werte sind möglich: "Zulassen", "Ablehnen"</param>
        <param name="ruleName">Der Name der Regel. Wenn die Eingabe mit jeder Sicherheitsregel nicht abgeglichen wird, wird es nicht angezeigt.</param>
        <summary>
            Initialisiert eine neue Instanz der VerificationIPFlowResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob der Datenverkehr zugelassen oder verweigert wird, ruft ab oder legt ihn fest.
            Folgende Werte sind möglich: "Zulassen", "Ablehnen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RuleName">
      <MemberSignature Language="C#" Value="public string RuleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RuleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.RuleName" />
      <MemberSignature Language="VB.NET" Value="Public Property RuleName As String" />
      <MemberSignature Language="F#" Value="member this.RuleName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VerificationIPFlowResult.RuleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ruleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Regel fest. Wenn die Eingabe mit jeder Sicherheitsregel nicht abgeglichen wird, wird es nicht angezeigt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>