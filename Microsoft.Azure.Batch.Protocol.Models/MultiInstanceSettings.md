<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Einstellungen auf, die angeben, wie eine Aufgabe mit mehreren Instanzen ausgeführt werden soll.
            </summary>
    <remarks>
            Mit mehreren Instanzen Tasks werden häufig verwendet, um MPI-Aufgaben zu unterstützen.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MultiInstanceSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; commonResourceFiles) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null, Optional commonResourceFiles As IList(Of ResourceFile) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings : string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings (coordinationCommandLine, numberOfInstances, commonResourceFiles)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="commonResourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine">Die auszuführende Befehlszeile auf den Serverknoten zum Koordinieren der beim Aktivieren der primären führt den Befehl "Task" main ".</param>
        <param name="numberOfInstances">Die Anzahl der Computeknoten, die vom Task benötigt werden.</param>
        <param name="commonResourceFiles">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile Koordinierung heruntergeladen wird.</param>
        <summary>
            Initialisiert eine neue Instanz der MultiInstanceSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonResourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder Festlegen einer Liste von Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile Koordinierung heruntergeladen wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Unterschied zwischen allgemeinen Ressourcendateien und Ressourcendateien Aufgabe ist, dass allgemeine Ressourcendateien für alle Unteraufgaben an, einschließlich der primären heruntergeladen werden, während nur für die primäre Aufgabe Ressourcendateien heruntergeladen werden. Beachten Sie außerdem, dass diese Ressourcendateien werden nicht auf das Arbeitsverzeichnis für den Task heruntergeladen, aber stattdessen auf das Stammverzeichnis des Vorgangs (ein Verzeichnis über das Arbeitsverzeichnis) heruntergeladen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="coordinationCommandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Befehlszeile auf den Serverknoten, zu ermöglichen, zum Koordinieren der Ausführung des primären den Befehl "Task" main "ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Typische Koordinierung über die Befehlszeile einen Hintergrunddienst startet und stellt sicher, dass der Dienst zum Verarbeiten von Nachrichten zwischen Knoten bereit ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numberOfInstances")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl von Serverknoten, die von der Aufgabe erforderlich sind.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, ist der Standardwert 1.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="multiInstanceSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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