<Type Name="ScaleAction" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction">
  <TypeSignature Language="C#" Value="public class ScaleAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleAction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleAction" />
  <TypeSignature Language="F#" Value="type ScaleAction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Parameter für die skalierungsaktion.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ScaleAction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleAction (Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection direction, Microsoft.Azure.Management.Monitor.Management.Models.ScaleType type, TimeSpan cooldown, string value = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection direction, valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleType type, valuetype System.TimeSpan cooldown, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection,Microsoft.Azure.Management.Monitor.Management.Models.ScaleType,System.TimeSpan,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (direction As ScaleDirection, type As ScaleType, cooldown As TimeSpan, Optional value As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction : Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection * Microsoft.Azure.Management.Monitor.Management.Models.ScaleType * TimeSpan * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction (direction, type, cooldown, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="direction" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleType" />
        <Parameter Name="cooldown" Type="System.TimeSpan" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="direction">die skalierungsrichtung. Gibt an, ob die skalierungsaktion erhöht oder verringert die Anzahl der Instanzen. Folgende Werte sind möglich: 'None', 'erhöhen","Verkleinern"</param>
        <param name="type">Der Typ der Aktion, die ausgeführt werden soll, wenn die skalierungsregel ausgelöst wird. Folgende Werte sind möglich: "changecount" "", "percentchangecount" "", "ExactCount"</param>
        <param name="cooldown">die Zeitspanne, die seit der letzten skalierungsaktion gewartet wird, bevor diese Aktion ausgeführt wird. Es muss zwischen 1 Woche und 1 Minute im ISO 8601-Format sein.</param>
        <param name="value">die Anzahl der Instanzen, die in der skalierungsaktion beteiligt sind. Dieser Wert muss 1 oder höher lauten. Der Standardwert ist 1.</param>
        <summary>
            Initialisiert eine neue Instanz der ScaleAction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cooldown">
      <MemberSignature Language="C#" Value="public TimeSpan Cooldown { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Cooldown" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Cooldown" />
      <MemberSignature Language="VB.NET" Value="Public Property Cooldown As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Cooldown : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Cooldown" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cooldown")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitspanne, die seit der letzten skalierungsaktion gewartet wird, bevor diese Aktion tritt auf. Es muss zwischen 1 Woche und 1 Minute im ISO 8601-Format sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As ScaleDirection" />
      <MemberSignature Language="F#" Value="member this.Direction : Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleDirection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Richtung der Skala fest. Gibt an, ob die skalierungsaktion erhöht oder verringert die Anzahl der Instanzen. Folgende Werte sind möglich: 'None', 'erhöhen","Verkleinern"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ScaleType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As ScaleType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.Monitor.Management.Models.ScaleType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Aktion, die ausgeführt werden soll, wenn die skalierungsregel ausgelöst wird. Folgende Werte sind möglich: "changecount" "", "percentchangecount" "", "ExactCount"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleAction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public string Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As String" />
      <MemberSignature Language="F#" Value="member this.Value : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Instanzen, die beteiligt sind, in der skalierungsaktion. Dieser Wert muss 1 oder höher lauten. Der Standardwert ist 1.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>