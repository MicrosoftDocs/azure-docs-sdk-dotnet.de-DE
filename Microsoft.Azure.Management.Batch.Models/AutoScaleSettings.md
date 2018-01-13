<Type Name="AutoScaleSettings" FullName="Microsoft.Azure.Management.Batch.Models.AutoScaleSettings">
  <TypeSignature Language="C#" Value="public class AutoScaleSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoScaleSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.AutoScaleSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoScaleSettings" />
  <TypeSignature Language="F#" Value="type AutoScaleSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="04685-101">Einstellungen für automatische Skalierung für den Pool.</span><span class="sxs-lookup"><span data-stu-id="04685-101">AutoScale settings for the pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04685-102">Initialisiert eine neue Instanz der AutoScaleSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="04685-102">Initializes a new instance of the AutoScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoScaleSettings (string formula, Nullable&lt;TimeSpan&gt; evaluationInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string formula, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; evaluationInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.#ctor(System.String,System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (formula As String, Optional evaluationInterval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.AutoScaleSettings : string * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Batch.Models.AutoScaleSettings" Usage="new Microsoft.Azure.Management.Batch.Models.AutoScaleSettings (formula, evaluationInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="formula" Type="System.String" />
        <Parameter Name="evaluationInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="formula"><span data-ttu-id="04685-103">Eine Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="04685-103">A formula for the desired number of compute nodes in the pool.</span></span></param>
        <param name="evaluationInterval"><span data-ttu-id="04685-104">Das Zeitintervall, an dem die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst werden soll.</span><span class="sxs-lookup"><span data-stu-id="04685-104">The time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span></param>
        <summary>
            <span data-ttu-id="04685-105">Initialisiert eine neue Instanz der AutoScaleSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="04685-105">Initializes a new instance of the AutoScaleSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EvaluationInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; EvaluationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; EvaluationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.EvaluationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property EvaluationInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.EvaluationInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.EvaluationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="evaluationInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04685-106">Ruft ab oder legt das Zeitintervall an, die Poolgröße gemäß Formel für automatische Skalierung automatisch angepasst.</span><span class="sxs-lookup"><span data-stu-id="04685-106">Gets or sets the time interval at which to automatically adjust the pool size according to the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="04685-107">Wenn nicht angegeben, ist der Standardwert 15 Minuten (PT15M).</span><span class="sxs-lookup"><span data-stu-id="04685-107">If omitted, the default value is 15 minutes (PT15M).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Formula">
      <MemberSignature Language="C#" Value="public string Formula { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Formula" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.Formula" />
      <MemberSignature Language="VB.NET" Value="Public Property Formula As String" />
      <MemberSignature Language="F#" Value="member this.Formula : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.Formula" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="formula")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="04685-108">Ruft ab oder legt eine Formel für die gewünschte Anzahl von Serverknoten im Pool.</span><span class="sxs-lookup"><span data-stu-id="04685-108">Gets or sets a formula for the desired number of compute nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoScaleSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoScaleSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="04685-109">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="04685-109">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="04685-110">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="04685-110">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>