<Type Name="ActivityLogAlertLeafCondition" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition">
  <TypeSignature Language="C#" Value="public class ActivityLogAlertLeafCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityLogAlertLeafCondition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityLogAlertLeafCondition" />
  <TypeSignature Language="F#" Value="type ActivityLogAlertLeafCondition = class" />
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
            Eine warnungsbedingung Aktivitätsprotokoll, die durch den Vergleich ein Protokoll-Feld "Aktivität" und Wert erfüllt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertLeafCondition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.#ctor" />
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
            Initialisiert eine neue Instanz der ActivityLogAlertLeafCondition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityLogAlertLeafCondition (string field, string equals);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string field, string equals) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (field As String, equals As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition : string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition (field, equals)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="field" Type="System.String" />
        <Parameter Name="equals" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="field">Der Name des Felds, das diese Bedingung überprüft. Die möglichen Werte für dieses Feld sind (Groß-/Kleinschreibung): "ResourceId", "Kategorie", 'Aufrufer', 'Ebene', "OperationName", "ResourceGroup" "", "ResourceProvider", "Status", "SubStatus", "ResourceType" oder etwas beginnend mit "Eigenschaften".</param>
        <param name="equals">Mit diesem Wert (Groß-/Kleinschreibung), um festzustellen, ob die Bedingung erfüllt ist, wird der Wert des Felds verglichen werden.</param>
        <summary>
            Initialisiert eine neue Instanz der ActivityLogAlertLeafCondition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public string Equals { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Equals" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.Equals" />
      <MemberSignature Language="VB.NET" Value="Public Property Equals As String" />
      <MemberSignature Language="F#" Value="member this.Equals : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.Equals" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="equals")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die der Wert des Felds verglichen werden soll, auf diesen Wert (Groß-/Kleinschreibung), um festzustellen, ob die Bedingung erfüllt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Field">
      <MemberSignature Language="C#" Value="public string Field { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Field" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.Field" />
      <MemberSignature Language="VB.NET" Value="Public Property Field As String" />
      <MemberSignature Language="F#" Value="member this.Field : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.Field" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="field")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Felds, das diese Bedingung überprüft. Die möglichen Werte für dieses Feld sind (Groß-/Kleinschreibung): "ResourceId", "Kategorie", 'Aufrufer', 'Ebene', "OperationName", "ResourceGroup" "", "ResourceProvider", "Status", "SubStatus", "ResourceType" oder etwas beginnend mit "Eigenschaften".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ActivityLogAlertLeafCondition.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="activityLogAlertLeafCondition.Validate " />
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