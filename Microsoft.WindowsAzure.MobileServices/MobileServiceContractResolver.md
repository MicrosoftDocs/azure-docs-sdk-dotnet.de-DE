<Type Name="MobileServiceContractResolver" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver">
  <TypeSignature Language="C#" Value="public class MobileServiceContractResolver : Newtonsoft.Json.Serialization.DefaultContractResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileServiceContractResolver extends Newtonsoft.Json.Serialization.DefaultContractResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileServiceContractResolver&#xA;Inherits DefaultContractResolver" />
  <TypeSignature Language="F#" Value="type MobileServiceContractResolver = class&#xA;    inherit DefaultContractResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Newtonsoft.Json.Serialization.DefaultContractResolver</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein <see cref="T:Newtonsoft.Json.Serialization.IContractResolver" /> Implementierung, die mit der <see cref="T:Microsoft.WindowsAzure.MobileServices.MobileServiceClient" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileServiceContractResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMemberValueProvider">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.IValueProvider CreateMemberValueProvider (System.Reflection.MemberInfo member);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.IValueProvider CreateMemberValueProvider(class System.Reflection.MemberInfo member) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateMemberValueProvider(System.Reflection.MemberInfo)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateMemberValueProvider (member As MemberInfo) As IValueProvider" />
      <MemberSignature Language="F#" Value="override this.CreateMemberValueProvider : System.Reflection.MemberInfo -&gt; Newtonsoft.Json.Serialization.IValueProvider" Usage="mobileServiceContractResolver.CreateMemberValueProvider member" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.IValueProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" />
      </Parameters>
      <Docs>
        <param name="member">Der Member.</param>
        <summary>
            Erstellt die <see cref="T:Newtonsoft.Json.Serialization.IValueProvider" /> zum Abrufen und Festlegen von Werten aus einem Element durch das Serialisierungsprogramm verwendet.
            </summary>
        <returns>Die <see cref="T:Newtonsoft.Json.Serialization.IValueProvider" /> zum Abrufen und Festlegen von Werten aus einem Element durch das Serialisierungsprogramm verwendet.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateObjectContract">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.JsonObjectContract CreateObjectContract (Type objectType);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.JsonObjectContract CreateObjectContract(class System.Type objectType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateObjectContract(System.Type)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateObjectContract (objectType As Type) As JsonObjectContract" />
      <MemberSignature Language="F#" Value="override this.CreateObjectContract : Type -&gt; Newtonsoft.Json.Serialization.JsonObjectContract" Usage="mobileServiceContractResolver.CreateObjectContract objectType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonObjectContract</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectType" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="objectType">To be added.</param>
        <summary>
            Erstellt eine <see cref="T:Newtonsoft.Json.Serialization.JsonObjectContract" /> bereitstellt Informationen wie der angegebene Typ zu JSON serialisiert werden soll.
            </summary>
        <returns>
            Die <see cref="T:Newtonsoft.Json.Serialization.JsonObjectContract" /> für den Typ.
            </returns>
        <remarks>
            Diese Methode wird überschrieben, um Typen abfangen, <see cref="T:System.Runtime.Serialization.DataMemberAttribute" /> auf einen oder mehrere Member ohne einen <see cref="T:System.Runtime.Serialization.DataContractAttribute" /> für den Typ selbst. Dieses verwendet, die unterstützt werden, sondern mehr ist, und für solche Typen muss daher eine Ausnahme ausgelöst werden. Die Ausnahme informiert den Entwickler über das ordnungsgemäße Attributierung des Typs mit dem <see cref="T:Newtonsoft.Json.JsonPropertyAttribute" /> statt der <see cref="T:System.Runtime.Serialization.DataMemberAttribute" />.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateProperties">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IList&lt;Newtonsoft.Json.Serialization.JsonProperty&gt; CreateProperties (Type type, Newtonsoft.Json.MemberSerialization memberSerialization);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IList`1&lt;class Newtonsoft.Json.Serialization.JsonProperty&gt; CreateProperties(class System.Type type, valuetype Newtonsoft.Json.MemberSerialization memberSerialization) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateProperties(System.Type,Newtonsoft.Json.MemberSerialization)" />
      <MemberSignature Language="F#" Value="override this.CreateProperties : Type * Newtonsoft.Json.MemberSerialization -&gt; System.Collections.Generic.IList&lt;Newtonsoft.Json.Serialization.JsonProperty&gt;" Usage="mobileServiceContractResolver.CreateProperties (type, memberSerialization)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Newtonsoft.Json.Serialization.JsonProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
        <Parameter Name="memberSerialization" Type="Newtonsoft.Json.MemberSerialization" />
      </Parameters>
      <Docs>
        <param name="type">
             Der Typ, für den zum Erstellen der Sammlung von <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> Instanzen.
             </param>
        <param name="memberSerialization">
             Gibt die elementserialisierungsoptionen für den Typ an.
             </param>
        <summary>
             Erstellt eine Auflistung von <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> Instanzen für die Elemente eines angegebenen Typs.
             </summary>
        <returns>
             Eine Auflistung von <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> Instanzen für die Elemente eines angegebenen Typs.
             </returns>
        <remarks>
             Diese Methode wird überschrieben, um die Id-Eigenschaft des Typs behandeln. Da mehrere Eigenschaftsnamen ("Id" mit unterschiedlicher Groß-/Kleinschreibung) alle als Id-Eigenschaft behandelt werden, müssen wir sicherstellen, dass nur eine Id-Eigenschaft für den Typ vorhanden ist. Darüber hinaus sollte die Id-Eigenschaft ignoriert werden, wenn es der Standardwert oder null ist und es immer in JSON, mit einem kleingeschriebenen "Id" Namen serialisiert sollte.
             
             Diese Methode überprüft außerdem eine gilt und Systemattributen-Eigenschaft.
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateProperty">
      <MemberSignature Language="C#" Value="protected override Newtonsoft.Json.Serialization.JsonProperty CreateProperty (System.Reflection.MemberInfo member, Newtonsoft.Json.MemberSerialization memberSerialization);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Newtonsoft.Json.Serialization.JsonProperty CreateProperty(class System.Reflection.MemberInfo member, valuetype Newtonsoft.Json.MemberSerialization memberSerialization) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.CreateProperty(System.Reflection.MemberInfo,Newtonsoft.Json.MemberSerialization)" />
      <MemberSignature Language="F#" Value="override this.CreateProperty : System.Reflection.MemberInfo * Newtonsoft.Json.MemberSerialization -&gt; Newtonsoft.Json.Serialization.JsonProperty" Usage="mobileServiceContractResolver.CreateProperty (member, memberSerialization)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" />
        <Parameter Name="memberSerialization" Type="Newtonsoft.Json.MemberSerialization" />
      </Parameters>
      <Docs>
        <param name="member">
            Die <see cref="T:System.Reflection.MemberInfo" /> für erstellt werden soll die <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />.
            </param>
        <param name="memberSerialization">
            Gibt die elementserialisierungsoptionen für das Element an.
            </param>
        <summary>
            Erstellt eine <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> für einen bestimmten <see cref="T:System.Reflection.MemberInfo" /> Instanz.
            </summary>
        <returns>
            Ein <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> für einen bestimmten <see cref="T:System.Reflection.MemberInfo" /> Instanz.
            </returns>
        <remarks>
            Diese Methode wird überschrieben, in der Reihenfolge, legen spezielle <see cref="T:Newtonsoft.Json.Serialization.IValueProvider" /> Implementierungen für bestimmte Eigenschaftentypen. Die Datumstypen (<see cref="T:System.DateTime" />, <see cref="T:System.DateTimeOffset" />) erfordern die Konvertierung in UTC-Datumsangaben bei der Serialisierung und in lokale Datumsangaben bei der Deserialisierung. Die numerischen Typen (<see cref="T:System.Int64" />, <see cref="T:System.UInt64" />, <see cref="T:System.Decimal" />) erfordern Überprüfungen, um sicherzustellen, dass auf dem Server nicht mit einfacher Genauigkeit verloren geht.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveIdProperty">
      <MemberSignature Language="C#" Value="public virtual Newtonsoft.Json.Serialization.JsonProperty ResolveIdProperty (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Newtonsoft.Json.Serialization.JsonProperty ResolveIdProperty(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveIdProperty(System.Type)" />
      <MemberSignature Language="F#" Value="abstract member ResolveIdProperty : Type -&gt; Newtonsoft.Json.Serialization.JsonProperty&#xA;override this.ResolveIdProperty : Type -&gt; Newtonsoft.Json.Serialization.JsonProperty" Usage="mobileServiceContractResolver.ResolveIdProperty type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type">
            Der Typ, für den beim Abrufen der Id <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />.
            </param>
        <summary>
            Gibt die Id <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> für den angegebenen Typ. Die <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> zum Get/Set-Id-Wert, der eine Instanz des angegebenen Typs verwendet werden kann.
            </summary>
        <returns>
            Die Id <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveProperty">
      <MemberSignature Language="C#" Value="public virtual Newtonsoft.Json.Serialization.JsonProperty ResolveProperty (System.Reflection.MemberInfo member);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Newtonsoft.Json.Serialization.JsonProperty ResolveProperty(class System.Reflection.MemberInfo member) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveProperty(System.Reflection.MemberInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveProperty (member As MemberInfo) As JsonProperty" />
      <MemberSignature Language="F#" Value="abstract member ResolveProperty : System.Reflection.MemberInfo -&gt; Newtonsoft.Json.Serialization.JsonProperty&#xA;override this.ResolveProperty : System.Reflection.MemberInfo -&gt; Newtonsoft.Json.Serialization.JsonProperty" Usage="mobileServiceContractResolver.ResolveProperty member" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.Serialization.JsonProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="member" Type="System.Reflection.MemberInfo" />
      </Parameters>
      <Docs>
        <param name="member">
            Die <see cref="T:System.Reflection.MemberInfo" /> für das Abrufen der <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" />.
            </param>
        <summary>
            Gibt die <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> für den angegebenen <see cref="T:System.Reflection.MemberInfo" /> Instanz.
            Die <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> dienen zum Abrufen von Informationen zur Funktionsweise des <see cref="T:System.Reflection.MemberInfo" /> serialisiert werden soll.
            </summary>
        <returns>
            Die <see cref="T:Newtonsoft.Json.Serialization.JsonProperty" /> für den angegebenen <see cref="T:System.Reflection.MemberInfo" /> Instanz.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolvePropertyName">
      <MemberSignature Language="C#" Value="protected override string ResolvePropertyName (string propertyName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string ResolvePropertyName(string propertyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolvePropertyName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ResolvePropertyName (propertyName As String) As String" />
      <MemberSignature Language="F#" Value="override this.ResolvePropertyName : string -&gt; string" Usage="mobileServiceContractResolver.ResolvePropertyName propertyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="propertyName">
            Der aufzulösende Eigenschaftsname.
            </param>
        <summary>
            Gibt den Namen, der serialisiert werden sollen in JSON für einen angegebenen Eigenschaftsnamen zurück.
            </summary>
        <returns>
            Der aufgelöste Eigenschaftsname.
            </returns>
        <remarks>
            Diese Methode wird überschrieben, um binnenmajuskel Eigenschaftsnamen zu unterstützen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveSystemProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties ResolveSystemProperties (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance valuetype Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties ResolveSystemProperties(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveSystemProperties(System.Type)" />
      <MemberSignature Language="F#" Value="abstract member ResolveSystemProperties : Type -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties&#xA;override this.ResolveSystemProperties : Type -&gt; Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties" Usage="mobileServiceContractResolver.ResolveSystemProperties type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.MobileServiceSystemProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type">Der Typ, für das die Systemeigenschaften abgerufen werden soll.</param>
        <summary>
            Gibt die Systemeigenschaften als eine durch Kommas getrennte Liste für einen angegebenen Typ zurück. Gibt null zurück, wenn der Typ nicht Hilfsmittel Eigenschaften unterstützt.
            </summary>
        <returns>
            Die Systemeigenschaften als eine durch Kommas getrennte Liste für den angegebenen Typ oder Null, wenn der Typ nicht Hilfsmittel Eigenschaften verfügt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveTableName">
      <MemberSignature Language="C#" Value="public virtual string ResolveTableName (Type type);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveTableName(class System.Type type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceContractResolver.ResolveTableName(System.Type)" />
      <MemberSignature Language="F#" Value="abstract member ResolveTableName : Type -&gt; string&#xA;override this.ResolveTableName : Type -&gt; string" Usage="mobileServiceContractResolver.ResolveTableName type" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="type" Type="System.Type" />
      </Parameters>
      <Docs>
        <param name="type">
            Der Typ für den Namen der Tabelle zurückgegeben.
            </param>
        <summary>
            Gibt einen Tabellennamen für einen Typ zurück, und sind für die tabellenumbenennung über DataContractAttribute, DataTableAttribute und/oder die jsonobjectattribute verantwortlich.
            </summary>
        <returns>
            Der Name der Tabelle.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>