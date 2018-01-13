<Type Name="AutoscaleProfile" FullName="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile">
  <TypeSignature Language="C#" Value="public class AutoscaleProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoscaleProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoscaleProfile" />
  <TypeSignature Language="F#" Value="type AutoscaleProfile = class" />
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
            Autoskalierungsprofil.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.#ctor" />
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
            Initialisiert eine neue Instanz der AutoscaleProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoscaleProfile (string name, Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity capacity, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; rules, Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow fixedDate = null, Microsoft.Azure.Management.Monitor.Management.Models.Recurrence recurrence = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity capacity, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; rules, class Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow fixedDate, class Microsoft.Azure.Management.Monitor.Management.Models.Recurrence recurrence) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.#ctor(System.String,Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule},Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow,Microsoft.Azure.Management.Monitor.Management.Models.Recurrence)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile : string * Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; * Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow * Microsoft.Azure.Management.Monitor.Management.Models.Recurrence -&gt; Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile (name, capacity, rules, fixedDate, recurrence)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="capacity" Type="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity" />
        <Parameter Name="rules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt;" />
        <Parameter Name="fixedDate" Type="Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow" />
        <Parameter Name="recurrence" Type="Microsoft.Azure.Management.Monitor.Management.Models.Recurrence" />
      </Parameters>
      <Docs>
        <param name="name">der Name des Profils.</param>
        <param name="capacity">Die Anzahl der Instanzen, die während dieses Profil verwendet werden können.</param>
        <param name="rules">die Auflistung von Regeln, die den Trigger und die Parameter für die skalierungsaktion bereitstellen. Es kann maximal 10 Regeln angegeben werden.</param>
        <param name="fixedDate">bestimmtes Datum und Uhrzeit für das Profil.
            Dieses Element wird nicht verwendet werden, wenn das Recurrence-Element verwendet wird.</param>
        <param name="recurrence">Die wiederholten Uhrzeiten, an denen dieses Profil beginnt. Dieses Element wird nicht verwendet werden, wenn das FixedDate-Element verwendet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoscaleProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As ScaleCapacity" />
      <MemberSignature Language="F#" Value="member this.Capacity : Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Instanzen, die während dieses Profil verwendet werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FixedDate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow FixedDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow FixedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.FixedDate" />
      <MemberSignature Language="VB.NET" Value="Public Property FixedDate As TimeWindow" />
      <MemberSignature Language="F#" Value="member this.FixedDate : Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.FixedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fixedDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.TimeWindow</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt bestimmte Datum und Uhrzeit für das Profil. Dieses Element wird nicht verwendet werden, wenn das Recurrence-Element verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            Ruft ab oder legt den Namen des Profils.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.Recurrence Recurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Management.Models.Recurrence Recurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Recurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property Recurrence As Recurrence" />
      <MemberSignature Language="F#" Value="member this.Recurrence : Microsoft.Azure.Management.Monitor.Management.Models.Recurrence with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Recurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.Recurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die wiederholten Zeitpunkten, an denen dieses Profil beginnt. Dieses Element wird nicht verwendet werden, wenn das FixedDate-Element verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Rules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; Rules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; Rules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Rules" />
      <MemberSignature Language="VB.NET" Value="Public Property Rules As IList(Of ScaleRule)" />
      <MemberSignature Language="F#" Value="member this.Rules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Rules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.ScaleRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung der Regeln, die den Trigger und die Parameter für die skalierungsaktion bereitstellen. Es kann maximal 10 Regeln angegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.AutoscaleProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="autoscaleProfile.Validate " />
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