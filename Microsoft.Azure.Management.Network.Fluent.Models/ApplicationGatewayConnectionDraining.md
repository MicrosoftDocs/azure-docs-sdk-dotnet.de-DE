<Type Name="ApplicationGatewayConnectionDraining" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayConnectionDraining" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayConnectionDraining extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayConnectionDraining" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayConnectionDraining = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Verbindung zu leeren ermöglicht geöffneten Verbindungen zu einem Back-End-Server auf aktiv sein, für einen festgelegten Zeitraum nach der Back-End-Server aus der Konfiguration entfernt wurde.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayConnectionDraining ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayConnectionDraining-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayConnectionDraining (bool enabled, int drainTimeoutInSec);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(bool enabled, int32 drainTimeoutInSec) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.#ctor(System.Boolean,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enabled As Boolean, drainTimeoutInSec As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining : bool * int -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining (enabled, drainTimeoutInSec)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="drainTimeoutInSec" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="enabled">Gibt an, ob Verbindung ein Ausgleich durchgeführt oder nicht aktiviert ist.</param>
        <param name="drainTimeoutInSec">Die Anzahl der Sekunden Verbindung leeren ist aktiv. Die zulässigen Werte reichen von 1 Sekunde bis 3600 Sekunden.</param>
        <summary>
            Initialisiert eine neue Instanz der ApplicationGatewayConnectionDraining-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DrainTimeoutInSec">
      <MemberSignature Language="C#" Value="public int DrainTimeoutInSec { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DrainTimeoutInSec" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.DrainTimeoutInSec" />
      <MemberSignature Language="VB.NET" Value="Public Property DrainTimeoutInSec As Integer" />
      <MemberSignature Language="F#" Value="member this.DrainTimeoutInSec : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.DrainTimeoutInSec" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="drainTimeoutInSec")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Sekunden, die Verbindung durch ein aktiv ist.
            Die zulässigen Werte reichen von 1 Sekunde bis 3600 Sekunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Verbindung ein Ausgleich durchgeführt wird oder nicht aktiviert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayConnectionDraining.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="applicationGatewayConnectionDraining.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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