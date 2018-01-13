<Type Name="StartTask" FullName="Microsoft.Azure.Management.Batch.Models.StartTask">
  <TypeSignature Language="C#" Value="public class StartTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.StartTask" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTask" />
  <TypeSignature Language="F#" Value="type StartTask = class" />
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
            Eine Aufgabe, die ausgeführt wird, wenn ein Serverknoten einen Pool in der Azure Batch-Dienst verknüpft, oder der Computeknoten neu gestartet, oder ein reimaging ausgeführt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.StartTask.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StartTask-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTask (string commandLine = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Management.Batch.Models.UserIdentity userIdentity = null, Nullable&lt;int&gt; maxTaskRetryCount = null, Nullable&lt;bool&gt; waitForSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Management.Batch.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.StartTask.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.EnvironmentSetting},Microsoft.Azure.Management.Batch.Models.UserIdentity,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.StartTask : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; * Microsoft.Azure.Management.Batch.Models.UserIdentity * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Batch.Models.StartTask" Usage="new Microsoft.Azure.Management.Batch.Models.StartTask (commandLine, resourceFiles, environmentSettings, userIdentity, maxTaskRetryCount, waitForSuccess)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Management.Batch.Models.UserIdentity" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine">Die Befehlszeile der Startaufgabe.</param>
        <param name="resourceFiles">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</param>
        <param name="environmentSettings">Eine Liste von umgebungsvariableneinstellungen für die Startaufgabe auszuführen.</param>
        <param name="userIdentity">Die Benutzeridentität, unter der die Startaufgabe ausgeführt wird.</param>
        <param name="maxTaskRetryCount">Gibt an, wie oft der Task maximal wiederholt werden kann.</param>
        <param name="waitForSuccess">Gibt an, ob der Batch-Dienst warten soll, für die Startaufgabe erfolgreich abgeschlossen (d. h. mit Exitcode 0 beendet) vor dem Planen alle Aufgaben auf den Computeknoten.</param>
        <summary>
            Initialisiert eine neue Instanz der StartTask-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Befehlszeile des Startaufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung. Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.
            Erforderlich, wenn alle anderen Eigenschaften für den StartTask angegeben werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für die Startaufgabe auszuführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl der Häufigkeit, mit die der Vorgang wiederholt werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist. Beachten Sie, dass dieser Wert die Anzahl der Wiederholungen ausdrücklich steuert. Der Batch-Dienst wiederholt den Task einmal und kann ihn anschließend bis zu diesem Grenzwert wiederholen. Beispielsweise ist die maximale Anzahl von Wiederholungsversuchen 3, Batch versucht die Aufgabe bis zu 4 Mal (einen ersten Versuch und 3 Wiederholungen). Wenn die maximale Anzahl von Wiederholungsversuchen 0 ist, wird der Batch-Dienst nicht die Aufgabe erneut versucht. Wenn die maximale Anzahl wiederholen ist-1, die Batch-Dienst Wiederholungen der Task unbegrenzt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Management.Batch.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Identität des Benutzers, unter der die Startaufgabe ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.StartTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.StartTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der Batch-Dienst warten soll, für die Startaufgabe erfolgreich abgeschlossen (d. h. mit Exitcode 0 beendet) vor dem Planen alle Aufgaben auf den Computeknoten.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn "true" und die Startaufgabe nicht auf einem Serverknoten, wiederholt der Batch-Dienst die Startaufgabe die maximale Anzahl von Wiederholungsversuchen ("maxtaskretrycount"). Wenn der Vorgang hat immer noch nicht erfolgreich abgeschlossen wurde nach aller Wiederholungsversuche, und klicken Sie dann auf die Batch-Dienst-Markierungen den Compute-Knoten kann nicht verwendet werden und wird nicht Planen von Aufgaben. Diese Bedingung kann über das Knotenstatus und Planung Fehlerdetail erkannt werden. Wenn "false", wartet der Batch-Dienst nicht für die Startaufgabe abgeschlossen. In diesem Fall können andere Aufgaben starten, auf dem Computeknoten ausgeführt werden, während die Startaufgabe ausgeführt wird; und auch wenn die Startaufgabe ein Fehler auftritt, neue Aufgaben weiterhin auf dem Knoten geplant werden. Der Standardwert ist false.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>