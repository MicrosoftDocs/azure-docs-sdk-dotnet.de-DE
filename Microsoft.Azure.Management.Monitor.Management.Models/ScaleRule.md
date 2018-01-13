<Type Name="ScaleRule" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule">
  <TypeSignature Language="C#" Value="public class ScaleRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleRule" />
  <TypeSignature Language="F#" Value="type ScaleRule = class" />
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
            Eine Regel, die den Trigger und die Parameter für die skalierungsaktion bereitstellen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.#ctor" />
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
            Initialisiert eine neue Instanz der ScaleRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleRule (Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger metricTrigger, Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction scaleAction);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger metricTrigger, class Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction scaleAction) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.#ctor(Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger,Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule : Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger * Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule (metricTrigger, scaleAction)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metricTrigger" Type="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" />
        <Parameter Name="scaleAction" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction" />
      </Parameters>
      <Docs>
        <param name="metricTrigger">Der Trigger, der zu einer skalierungsaktion führt.</param>
        <param name="scaleAction">Die Parameter für die skalierungsaktion.</param>
        <summary>
            Initialisiert eine neue Instanz der ScaleRule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricTrigger">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger MetricTrigger { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger MetricTrigger" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.MetricTrigger" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricTrigger As MetricTrigger" />
      <MemberSignature Language="F#" Value="member this.MetricTrigger : Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.MetricTrigger" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricTrigger")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Trigger, der zu einer skalierungsaktion führt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleAction">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction ScaleAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction ScaleAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.ScaleAction" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleAction As ScaleAction" />
      <MemberSignature Language="F#" Value="member this.ScaleAction : Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.ScaleAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scaleAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Parameter für die skalierungsaktion fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleRule.Validate " />
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
  </Members>
</Type>