<Type Name="ScaleCapacity" FullName="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity">
  <TypeSignature Language="C#" Value="public class ScaleCapacity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScaleCapacity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity" />
  <TypeSignature Language="VB.NET" Value="Public Class ScaleCapacity" />
  <TypeSignature Language="F#" Value="type ScaleCapacity = class" />
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
            Die Anzahl der Instanzen, die während dieses Profil verwendet werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleCapacity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.#ctor" />
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
            Initialisiert eine neue Instanz der ScaleCapacity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScaleCapacity (string minimum, string maximum, string defaultProperty);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string minimum, string maximum, string defaultProperty) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (minimum As String, maximum As String, defaultProperty As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity : string * string * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity (minimum, maximum, defaultProperty)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="minimum" Type="System.String" />
        <Parameter Name="maximum" Type="System.String" />
        <Parameter Name="defaultProperty" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="minimum">die Mindestanzahl der Instanzen für die Ressource.</param>
        <param name="maximum">die maximale Anzahl der Instanzen für die Ressource. Die tatsächliche maximale Anzahl der Instanzen wird durch die Kerne beschränkt, die im Abonnement verfügbar sind.</param>
        <param name="defaultProperty">die Anzahl der Instanzen, die festgelegt wird, wenn Metriken nicht für die Auswertung verfügbar sind. Der Standardwert wird nur verwendet, wenn die aktuelle instanzanzahl niedriger als der Standardwert ist.</param>
        <summary>
            Initialisiert eine neue Instanz der ScaleCapacity-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultProperty">
      <MemberSignature Language="C#" Value="public string DefaultProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.DefaultProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultProperty As String" />
      <MemberSignature Language="F#" Value="member this.DefaultProperty : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.DefaultProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="default")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Instanzen, die festgelegt wird, wenn Metriken nicht für die Auswertung verfügbar sind. Der Standardwert wird nur verwendet, wenn die aktuelle instanzanzahl niedriger als der Standardwert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public string Maximum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public Property Maximum As String" />
      <MemberSignature Language="F#" Value="member this.Maximum : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl der Instanzen für die Ressource. Die tatsächliche maximale Anzahl der Instanzen wird durch die Kerne beschränkt, die im Abonnement verfügbar sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public string Minimum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public Property Minimum As String" />
      <MemberSignature Language="F#" Value="member this.Minimum : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Mindestanzahl der Instanzen für die Ressource fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.ScaleCapacity.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scaleCapacity.Validate " />
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