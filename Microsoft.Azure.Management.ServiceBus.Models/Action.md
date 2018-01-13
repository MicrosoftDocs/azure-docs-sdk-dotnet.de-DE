<Type Name="Action" FullName="Microsoft.Azure.Management.ServiceBus.Models.Action">
  <TypeSignature Language="C#" Value="public class Action" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Action extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.Action" />
  <TypeSignature Language="VB.NET" Value="Public Class Action" />
  <TypeSignature Language="F#" Value="type Action = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt Filteraktionen, die zulässig sind, für die Transformation einer Nachricht, die von einem Filterausdruck abgeglichen wurden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Action ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Action.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse Aktion an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Action (string sqlExpression = null, Nullable&lt;int&gt; compatibilityLevel = null, Nullable&lt;bool&gt; requiresPreprocessing = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string sqlExpression, valuetype System.Nullable`1&lt;int32&gt; compatibilityLevel, valuetype System.Nullable`1&lt;bool&gt; requiresPreprocessing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.Action.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional sqlExpression As String = null, Optional compatibilityLevel As Nullable(Of Integer) = null, Optional requiresPreprocessing As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.Action : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.ServiceBus.Models.Action" Usage="new Microsoft.Azure.Management.ServiceBus.Models.Action (sqlExpression, compatibilityLevel, requiresPreprocessing)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sqlExpression" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requiresPreprocessing" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlExpression">SQL-Ausdruck. z. B. MyProperty = 'ABC'</param>
        <param name="compatibilityLevel">Diese Eigenschaft ist für eine spätere Verwendung vorgesehen. Ein Ganzzahlwert, mit dem Kompatibilitätsgrad derzeit fest programmiert, dass 20.</param>
        <param name="requiresPreprocessing">Ein Wert, der angibt, ob die Aktion für eine vorverarbeitung erforderlich ist.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Aktion an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CompatibilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Action.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property CompatibilityLevel As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Action.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="compatibilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt diese Eigenschaft ist für die zukünftige Verwendung reserviert. Ein Ganzzahlwert, mit dem Kompatibilitätsgrad derzeit fest programmiert, dass 20.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresPreprocessing">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequiresPreprocessing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequiresPreprocessing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Action.RequiresPreprocessing" />
      <MemberSignature Language="VB.NET" Value="Public Property RequiresPreprocessing As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequiresPreprocessing : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Action.RequiresPreprocessing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requiresPreprocessing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Wert, der angibt, ob die Aktion für eine vorverarbeitung erforderlich ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlExpression">
      <MemberSignature Language="C#" Value="public string SqlExpression { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlExpression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.Action.SqlExpression" />
      <MemberSignature Language="VB.NET" Value="Public Property SqlExpression As String" />
      <MemberSignature Language="F#" Value="member this.SqlExpression : string with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.Action.SqlExpression" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sqlExpression")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die SQL-Ausdruck. z. B. MyProperty = 'ABC'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>