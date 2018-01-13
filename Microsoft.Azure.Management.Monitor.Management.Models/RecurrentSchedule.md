<Type Name="RecurrentSchedule" FullName="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule">
  <TypeSignature Language="C#" Value="public class RecurrentSchedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecurrentSchedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class RecurrentSchedule" />
  <TypeSignature Language="F#" Value="type RecurrentSchedule = class" />
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
            Die planungseinschränkungen für den Beginn des Profils.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrentSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.#ctor" />
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
            Initialisiert eine neue Instanz der RecurrentSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecurrentSchedule (string timeZone, System.Collections.Generic.IList&lt;string&gt; days, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; hours, System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timeZone, class System.Collections.Generic.IList`1&lt;string&gt; days, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; hours, class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.Nullable{System.Int32}},System.Collections.Generic.IList{System.Nullable{System.Int32}})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timeZone As String, days As IList(Of String), hours As IList(Of Nullable(Of Integer)), minutes As IList(Of Nullable(Of Integer)))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule : string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; * System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; -&gt; Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule (timeZone, days, hours, minutes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="days" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="hours" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
        <Parameter Name="minutes" Type="System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="timeZone">die Zeitzone für die Stunden des Profils.
            Einige Beispiele für gültige Zeitzonen sind: Datumsgrenze Standard Time, UTC bis 11, Hawaii Normalzeit, Alaska Normalzeit, Pazifik Normalzeit (Mexiko), Pacific Standard Time, uns Mountain Standard Time, Mountain Normalzeit (Mexiko), Mountain Standard Time, Mittelamerikanische Normalzeit, Central Normalzeit, Central Normalzeit (Mexiko), Kanada Central Normalzeit, SA Pacific Standard Time, Eastern Standard Time, USA Eastern Standard Time, Venezuela Normalzeit , Paraguay Normalzeit, Atlantik Normalzeit, Central Portugiesisch (Brasilien) Normalzeit, SA Western Normalzeit, Pazifik SA Normalzeit, Neufundland Normalzeit Östl. Südamerika Normalzeit, Argentinien Normalzeit, SA Eastern Standard Time, Grönland Normalzeit, Montevideo Normalzeit, Bahia Normalzeit, UTC-02, Mittelatlantik Normalzeit, Azoren Normalzeit, Kap Verde Normalzeit, Marokko Normalzeit, UTC, Normalzeit GMT, Greenwich Normalzeit , Mitteleuropäische Zeit, Mitteleuropäische Zeit, Mitteleuropäische Zeit, Mitteleuropäische Zeit, West-Zentralafrika Normalzeit, Namibia Normalzeit, Jordanien Normalzeit, Osteuropäische Normalzeit, Naher Osten Normalzeit (Ägypten) aufhalten Normalzeit, Syrien Normalzeit, Osteuropa Normalzeit, Südafrika Normalzeit, Osteuropäische Normalzeit, Türkei Normalzeit, Israel Zeit, Kaliningrad Normalzeit, Libyen Normalzeit , Arabische Normalzeit, Arabische Normalzeit, Belarus Normalzeit, Russisch Normalzeit, E. Afrika Normalzeit, Iran Normalzeit, Arabische Normalzeit, Aserbaidschan Normalzeit, Russische Föderation Zeitzone 3, Mauritius Normalzeit, Georgisch Normalzeit, Kaukasische Normalzeit, Afghanistan Normalzeit, West Asien Normalzeit, Jekaterinburgische Normalzeit, Pakistan Normalzeit, Indien Normalzeit, Sri Lanka Normalzeit, Nepal Normalzeit , Zentralasien Normalzeit, Bangladesch Normalzeit, Nord-Zentralasien Normalzeit, Myanmar Normalzeit, südostasiatische Normalzeit, Ost-Nordasiatische Normalzeit, China Normalzeit, Ost-Nordasiatische Normalzeit, Singapur Normalzeit, West Australia Standard Time, Taipeh Normalzeit, Ulan-Bator Normalzeit, Tokyo Normalzeit, Korea Normalzeit, Jakutsk Standard Time "CEN" Australia Standard Time, Zentralaustralische Normalzeit, Ostaustralische Normalzeit, Ostaustralische Normalzeit, West Pacific Standard Time, Tasmanien Normalzeit, Magadan Normalzeit, Wladiwostok Normalzeit, Russische Föderation Zeitzone 10, zentralen Pacific Standard Time, Russische Föderation Zeitzone 11, Neuseeland Normalzeit, UTC + 12 Fidschi Normalzeit, Kamtschatka Normalzeit, Tonga Normalzeit, Samoa Normalzeit, Zeile Inseln Normalzeit</param>
        <param name="days">die Auflistung der Tage, an denen das Profil in Kraft tritt. Mögliche Werte sind Sonntag bis Samstag.</param>
        <param name="hours">Eine Auflistung von Stunden, die das Profil in Kraft tritt. Unterstützte Werte sind 0 bis 23, auf dem 24-Stunden-Format (AM/PM-Zeiten werden nicht unterstützt).</param>
        <param name="minutes">Eine Auflistung von Minuten, in denen das Profil in Kraft tritt.</param>
        <summary>
            Initialisiert eine neue Instanz der RecurrentSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Days">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Days { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Days" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Days" />
      <MemberSignature Language="VB.NET" Value="Public Property Days As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Days : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Days" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="days")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung der Tage, an denen das Profil in Kraft tritt. Mögliche Werte sind Sonntag bis Samstag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Hours">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; Hours { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; Hours" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Hours" />
      <MemberSignature Language="VB.NET" Value="Public Property Hours As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.Hours : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Hours" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hours")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Auflistung von Stunden, die das Profil in Kraft tritt. Unterstützte Werte sind 0 bis 23, auf dem 24-Stunden-Format (AM/PM-Zeiten werden nicht unterstützt).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minutes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; Minutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype System.Nullable`1&lt;int32&gt;&gt; Minutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Minutes" />
      <MemberSignature Language="VB.NET" Value="Public Property Minutes As IList(Of Nullable(Of Integer))" />
      <MemberSignature Language="F#" Value="member this.Minutes : System.Collections.Generic.IList&lt;Nullable&lt;int&gt;&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Minutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Nullable&lt;System.Int32&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Auflistung von Minuten, in denen das Profil in Kraft tritt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitzone für die Stunden des Profils. Einige Beispiele für gültige Zeitzonen sind: Datumsgrenze Standard Time, UTC bis 11, Hawaii Normalzeit, Alaska Normalzeit, Pazifik Normalzeit (Mexiko), Pacific Standard Time, uns Mountain Standard Time, Mountain Normalzeit (Mexiko), Mountain Standard Time, Mittelamerikanische Normalzeit, Central Normalzeit, Central Normalzeit (Mexiko), Kanada Central Normalzeit, SA Pacific Standard Time, Eastern Standard Time, USA Eastern Standard Time, Venezuela Normalzeit , Paraguay Normalzeit, Atlantik Normalzeit, Central Portugiesisch (Brasilien) Normalzeit, SA Western Normalzeit, Pazifik SA Normalzeit, Neufundland Normalzeit Östl. Südamerika Normalzeit, Argentinien Normalzeit, SA Eastern Standard Time, Grönland Normalzeit, Montevideo Normalzeit, Bahia Normalzeit, UTC-02, Mittelatlantik Normalzeit, Azoren Normalzeit, Kap Verde Normalzeit, Marokko Normalzeit, UTC, Normalzeit GMT, Greenwich Normalzeit , Mitteleuropäische Zeit, Mitteleuropäische Zeit, Mitteleuropäische Zeit, Mitteleuropäische Zeit, West-Zentralafrika Normalzeit, Namibia Normalzeit, Jordanien Normalzeit, Osteuropäische Normalzeit, Naher Osten Normalzeit (Ägypten) aufhalten Normalzeit, Syrien Normalzeit, Osteuropa Normalzeit, Südafrika Normalzeit, Osteuropäische Normalzeit, Türkei Normalzeit, Israel Zeit, Kaliningrad Normalzeit, Libyen Normalzeit , Arabische Normalzeit, Arabische Normalzeit, Belarus Normalzeit, Russisch Normalzeit, E. Afrika Normalzeit, Iran Normalzeit, Arabische Normalzeit, Aserbaidschan Normalzeit, Russische Föderation Zeitzone 3, Mauritius Normalzeit, Georgisch Normalzeit, Kaukasische Normalzeit, Afghanistan Normalzeit, West Asien Normalzeit, Jekaterinburgische Normalzeit, Pakistan Normalzeit, Indien Normalzeit, Sri Lanka Normalzeit, Nepal Normalzeit , Zentralasien Normalzeit, Bangladesch Normalzeit, Nord-Zentralasien Normalzeit, Myanmar Normalzeit, südostasiatische Normalzeit, Ost-Nordasiatische Normalzeit, China Normalzeit, Ost-Nordasiatische Normalzeit, Singapur Normalzeit, West Australia Standard Time, Taipeh Normalzeit, Ulan-Bator Normalzeit, Tokyo Normalzeit, Korea Normalzeit, Jakutsk Standard Time "CEN" Australia Standard Time, Zentralaustralische Normalzeit, Ostaustralische Normalzeit, Ostaustralische Normalzeit, West Pacific Standard Time, Tasmanien Normalzeit, Magadan Normalzeit, Wladiwostok Normalzeit, Russische Föderation Zeitzone 10, zentralen Pacific Standard Time, Russische Föderation Zeitzone 11, Neuseeland Normalzeit, UTC + 12 Fidschi Normalzeit, Kamtschatka Normalzeit, Tonga Normalzeit, Samoa Normalzeit, Zeile Inseln Normalzeit
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.RecurrentSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="recurrentSchedule.Validate " />
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